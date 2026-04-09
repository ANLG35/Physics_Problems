# Physics Analysis: One-Dimensional Restoring Force

## 1. Equation of Motion and Solution
For a particle of mass $m$ subject to a force $F(x) = -kx$, we apply **Newton's Second Law**:

$$F = ma \implies -kx = m \frac{d^2x}{dt^2}$$

Rearranging into the standard form of a linear second-order differential equation:
$$\frac{d^2x}{dt^2} + \frac{k}{m}x = 0$$

Letting $\omega^2 = \frac{k}{m}$, the general solution is:
$$x(t) = A \cos(\omega t + \phi)$$
*Where $A$ is amplitude and $\phi$ is the phase constant.*

---

## 2. Work Done Calculation
Work done by the force during displacement from $0$ to $x_0$ is given by the integral:

$$W = \int_{0}^{x_0} F(x) \, dx = \int_{0}^{x_0} (-kx) \, dx$$
$$W = \left[ -\frac{1}{2}kx^2 \right]_{0}^{x_0} = -\frac{1}{2}kx_0^2$$

---

## 3. Potential Energy Interpretation
Potential energy $U(x)$ is defined as the negative of the work done by a conservative force. Since the work done by the system is negative, the potential energy stored in the system increases:
$$U(x) = -W = \frac{1}{2}kx^2$$

---

## 4. Relationship Verification ($F = -dU/dx$)
To verify the relationship, we take the negative derivative of the potential energy function:
$$-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right)$$
$$-\frac{dU}{dx} = -( \frac{1}{2}k \cdot 2x ) = -kx$$
Since $-kx = F(x)$, the relationship is **verified**.

---

## 5. Visual Representation


* **$F(x)$ Graph:** A straight line passing through the origin with a negative slope (linear restoring force).
* **$U(x)$ Graph:** A parabola opening upwards with its vertex at the origin (potential well).
