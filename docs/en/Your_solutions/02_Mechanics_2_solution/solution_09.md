# Physics Problem: Vertical Motion with Linear Air Drag

## Problem Statement
We have the equation of motion:
$$m \frac{dv}{dt} = -mg - kv$$
with initial conditions $v(0) = v_0$ and $x(0) = 10$.
1. Solve the equation by analytical methods.
2. Determine the maximum height.
3. Compare with the case without drag.
4. Perform a numerical simulation using Python.

---

## 1. Analytical Solution

### Finding Velocity $v(t)$
Starting with Newton's Second Law:
$$m \frac{dv}{dt} = -mg - kv \implies \frac{dv}{dt} = -g - \frac{k}{m}v = -\frac{k}{m} \left(v + \frac{mg}{k}\right)$$

Separating variables and integrating:
$$\int_{v_0}^{v} \frac{dv}{v + \frac{mg}{k}} = \int_{0}^{t} -\frac{k}{m} dt$$
$$\ln\left( \frac{v + \frac{mg}{k}}{v_0 + \frac{mg}{k}} \right) = -\frac{k}{m}t$$

Taking the exponential of both sides and solving for $v(t)$:
$$v(t) = \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t} - \frac{mg}{k}$$

### Finding Position $x(t)$
To find the position, we integrate the velocity function $x(t) = \int v(t) dt$:
$$x(t) = \int \left[ \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t} - \frac{mg}{k} \right] dt$$
$$x(t) = -\frac{m}{k}\left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t} - \frac{mg}{k}t + C$$

Using the initial condition $x(0) = 10$:
$$10 = -\frac{m}{k}\left(v_0 + \frac{mg}{k}\right) + C \implies C = 10 + \frac{m}{k}\left(v_0 + \frac{mg}{k}\right)$$

Substitute $C$ back into the equation:
**$$x(t) = 10 + \frac{m}{k}\left(v_0 + \frac{mg}{k}\right)\left(1 - e^{-\frac{k}{m}t}\right) - \frac{mg}{k}t$$**

---

## 2. Maximum Height
Maximum height occurs when the velocity becomes zero ($v(t_{max}) = 0$).

Setting the velocity equation to zero:
$$0 = \left(v_0 + \frac{mg}{k}\right)e^{-\frac{k}{m}t_{max}} - \frac{mg}{k}$$
$$e^{\frac{k}{m}t_{max}} = \frac{v_0 + \frac{mg}{k}}{\frac{mg}{k}} = 1 + \frac{kv_0}{mg}$$
**$$t_{max} = \frac{m}{k} \ln\left(1 + \frac{kv_0}{mg}\right)$$**

Substitute $t_{max}$ into $x(t)$ to find $H_{max}$:
**$$H_{max} = 10 + \frac{m v_0}{k} - \frac{m^2 g}{k^2}\ln\left(1 + \frac{k v_0}{m g}\right)$$**

---

## 3. Comparison with the "No Drag" Case ($k \to 0$)
Without air drag, the equations simplify to standard kinematics ($a = -g$):
* **Velocity:** $v(t) = v_0 - gt$
* **Position:** $x(t) = 10 + v_0t - \frac{1}{2}gt^2$
* **Max Height:** $H_{nodrag} = 10 + \frac{v_0^2}{2g}$

**Comparison:** Because linear drag introduces an extra downward force (while ascending) and dissipates mechanical energy, the projectile reaches a lower maximum height ($H_{max} < H_{nodrag}$) and takes less time to reach that peak ($t_{max} < t_{nodrag}$) compared to the vacuum scenario.

---

## 4. Numerical Simulation (Python)
Here is a Python script using `scipy` and `matplotlib` to simulate and plot both conditions.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import odeint

# Parameters (can be adjusted)
m = 1.0     # mass (kg)
g = 9.81    # gravity (m/s^2)
k = 0.5     # drag coefficient (kg/s)
v0 = 20.0   # initial velocity (m/s)
x0 = 10.0   # initial position (m)

# Differential equation for Drag Case
def deriv(y, t, m, g, k):
    x, v = y
    dxdt = v
    dvdt = -g - (k/m)*v
    return [dxdt, dvdt]

# Time array
t = np.linspace(0, 4, 200)

# Solve ODE for drag
y0 = [x0, v0]
sol = odeint(deriv, y0, t, args=(m, g, k))
x_drag = sol[:, 0]

# Calculate No Drag case
x_nodrag = x0 + v0*t - 0.5*g*t**2

# Plotting
plt.figure(figsize=(8,5))
plt.plot(t, x_drag, label=f'With Linear Drag (k={k})', color='red')
plt.plot(t, x_nodrag, label='No Drag (Vacuum)', linestyle='--', color='blue')

# Formatting
plt.ylim(bottom=0)
plt.xlim(left=0, right=4)
plt.xlabel('Time (s)')
plt.ylabel('Height (m)')
plt.title('Vertical Projectile Motion: Drag vs. No Drag')
plt.legend()
plt.grid(True)
plt.show()
