# Physics Problem: Mass-Spring System Dynamics

## Problem Statement
A $10\text{ kg}$ mass is attached to a spring and oscillates according to the equation:
$$x(t) = 0.2 \cos(10\pi t)$$
where $x$ is in meters and $t$ is in seconds.

## 1. Finding the Spring Constant ($k$)
The general equation for simple harmonic motion is:
$$x(t) = A \cos(\omega t + \phi)$$

By comparing this to the given equation $x(t) = 0.2 \cos(10\pi t)$, we identify:
* Amplitude ($A$) = $0.2\text{ m}$
* Angular frequency ($\omega$) = $10\pi\text{ rad/s}$
* Mass ($m$) = $10\text{ kg}$

The relationship between angular frequency, mass, and the spring constant is:
$$\omega = \sqrt{\frac{k}{m}} \implies k = m\omega^2$$

Substituting the values:
$$k = 10 \times (10\pi)^2$$
$$k = 10 \times 100\pi^2$$
**$k = 1000\pi^2 \approx 9869.6\text{ N/m}$**

---

## 2. Finding the Total Mechanical Energy ($E$)
The total mechanical energy in a mass-spring system is constant and is given by:
$$E = \frac{1}{2} k A^2$$

Using our calculated value for $k$ and the given amplitude $A$:
$$E = \frac{1}{2} (1000\pi^2) (0.2)^2$$
$$E = 500\pi^2 \times 0.04$$
**$E = 20\pi^2 \approx 197.39\text{ Joules}$**
