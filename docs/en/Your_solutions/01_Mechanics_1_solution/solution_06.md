## Problem: Variable Velocity

**Given:**
* Velocity function: $v(t) = t^2 + 2t - 5$
* Initial position: $x(0) = 4$ at $t = 0$
* Find: Position ($x$) and Acceleration ($a$) at $t = 3$

---

### 1. Finding Acceleration at $t = 3$
Acceleration is the derivative of velocity with respect to time:
$$a(t) = \frac{dv}{dt}$$
$$a(t) = \frac{d}{dt}(t^2 + 2t - 5) = 2t + 2$$

Now, substitute $t = 3$:
$$a(3) = 2(3) + 2 = 8 \text{ m/s}^2$$

---

### 2. Finding Position at $t = 3$
Position is the integral of velocity with respect to time:
$$x(t) = \int v(t) \, dt = \int (t^2 + 2t - 5) \, dt$$
$$x(t) = \frac{t^3}{3} + t^2 - 5t + C$$

Use the initial condition $x(0) = 4$ to find $C$:
$$4 = \frac{0^3}{3} + 0^2 - 5(0) + C \implies C = 4$$
So, the position function is: $x(t) = \frac{t^3}{3} + t^2 - 5t + 4$

Now, substitute $t = 3$:
$$x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4$$
$$x(3) = 9 + 9 - 15 + 4 = 7$$

**Final Results:**
* **Acceleration at $t=3$:** $8 \text{ m/s}^2$
* **Position at $t=3$:** $x = 7$
