# Physics Problem: Particle Dynamics in a Time-Dependent Force Field

## Problem Statement
A particle of mass $m = 3\text{ kg}$ moves in a force field $\vec{F}(t)$ defined as:
$$\vec{F}(t) = (15t)\hat{i} + (3t - 12)\hat{j} + (-6t^2)\hat{k}$$
Initial conditions at $t = 0$:
* Position: $\vec{r}_0 = (5, 2, -3)\text{ m}$
* Velocity: $\vec{v}_0 = (2, 0, 1)\text{ m/s}$

Find the dependence of velocity $\vec{v}(t)$ and position $\vec{r}(t)$ on time.

---

## Solution

### 1. Acceleration ($\vec{a}$)
Using Newton's Second Law, $\vec{a}(t) = \frac{\vec{F}(t)}{m}$:
$$\vec{a}(t) = \frac{1}{3} (15t, 3t - 12, -6t^2)$$
**$$\vec{a}(t) = (5t)\hat{i} + (t - 4)\hat{j} + (-2t^2)\hat{k}$$**

### 2. Velocity ($\vec{v}$)
Velocity is the integral of acceleration: $\vec{v}(t) = \int \vec{a}(t) dt + \vec{v}_0$.

* $v_x(t) = \int 5t \, dt = \frac{5}{2}t^2 + C_1 \implies v_x(0) = 2 \therefore C_1 = 2$
* $v_y(t) = \int (t - 4) \, dt = \frac{1}{2}t^2 - 4t + C_2 \implies v_y(0) = 0 \therefore C_2 = 0$
* $v_z(t) = \int -2t^2 \, dt = -\frac{2}{3}t^3 + C_3 \implies v_z(0) = 1 \therefore C_3 = 1$

**$$\vec{v}(t) = (\frac{5}{2}t^2 + 2)\hat{i} + (\frac{1}{2}t^2 - 4t)\hat{j} + (-\frac{2}{3}t^3 + 1)\hat{k}$$**

### 3. Position ($\vec{r}$)
Position is the integral of velocity: $\vec{r}(t) = \int \vec{v}(t) dt + \vec{r}_0$.

* $x(t) = \int (\frac{5}{2}t^2 + 2) \, dt = \frac{5}{6}t^3 + 2t + D_1 \implies x(0) = 5 \therefore D_1 = 5$
* $y(t) = \int (\frac{1}{2}t^2 - 4t) \, dt = \frac{1}{6}t^3 - 2t^2 + D_2 \implies y(0) = 2 \therefore D_2 = 2$
* $z(t) = \int (-\frac{2}{3}t^3 + 1) \, dt = -\frac{1}{6}t^4 + t + D_3 \implies z(0) = -3 \therefore D_3 = -3$

**$$\vec{r}(t) = (\frac{5}{6}t^3 + 2t + 5)\hat{i} + (\frac{1}{6}t^3 - 2t^2 + 2)\hat{j} + (-\frac{1}{6}t^4 + t - 3)\hat{k}$$**
