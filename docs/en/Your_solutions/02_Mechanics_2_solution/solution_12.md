# Physics Problem: Constant Force Dynamics and Work-Energy Theorem

## Problem Statement
A constant force acts on a body of mass $m = 2\text{ kg}$:
$$\vec{F} = (6\hat{i} + 2\hat{j})\text{ N}$$
The body starts with:
* Initial velocity: $\vec{v}(0) = (1, -1)\text{ m/s}$
* Initial position: $\vec{r}(0) = (0, 0)\text{ m}$

Tasks: Determine acceleration, velocity, position, draw trajectory, calculate work at $t=3\text{ s}$, and verify the Work-Energy Theorem.

---

## 1. Acceleration ($\vec{a}$)
Using Newton's Second Law: $\vec{a} = \frac{\vec{F}}{m}$
$$\vec{a} = \frac{(6, 2)}{2} = (3, 1)\text{ m/s}^2$$
**$$\vec{a}(t) = 3\hat{i} + 1\hat{j}$$** (Constant)

## 2. Velocity ($\vec{v}(t)$)
Integrating acceleration: $\vec{v}(t) = \vec{a}t + \vec{v}_0$
$$\vec{v}(t) = (3, 1)t + (1, -1)$$
**$$\vec{v}(t) = (3t + 1)\hat{i} + (t - 1)\hat{j}$$**

## 3. Position ($\vec{r}(t)$)
Integrating velocity: $\vec{r}(t) = \frac{1}{2}\vec{a}t^2 + \vec{v}_0t + \vec{r}_0$
$$\vec{r}(t) = \frac{1}{2}(3, 1)t^2 + (1, -1)t + (0, 0)$$
**$$\vec{r}(t) = (1.5t^2 + t)\hat{i} + (0.5t^2 - t)\hat{j}$$**

## 4. Work Done at $t = 3\text{ s}$
First, find the displacement $\Delta\vec{r}$ at $t = 3$:
$x(3) = 1.5(3^2) + 3 = 13.5 + 3 = 16.5\text{ m}$
$y(3) = 0.5(3^2) - 3 = 4.5 - 3 = 1.5\text{ m}$
$\Delta\vec{r} = (16.5, 1.5)\text{ m}$

Work ($W = \vec{F} \cdot \Delta\vec{r}$):
$$W = (6 \times 16.5) + (2 \times 1.5)$$
$$W = 99 + 3 = 102\text{ Joules}$$

## 5. Work-Energy Theorem Verification
The theorem states $W = \Delta K = K_f - K_i$.

* **Initial Kinetic Energy ($K_i$):**
$v(0)^2 = 1^2 + (-1)^2 = 2$
$K_i = \frac{1}{2}mv_0^2 = \frac{1}{2}(2)(2) = 2\text{ J}$

* **Final Kinetic Energy at $t = 3$ ($K_f$):**
$v_x(3) = 3(3) + 1 = 10$
$v_y(3) = 3 - 1 = 2$
$v(3)^2 = 10^2 + 2^2 = 104$
$K_f = \frac{1}{2}mv_f^2 = \frac{1}{2}(2)(104) = 104\text{ J}$

* **Change in Kinetic Energy ($\Delta K$):**
$\Delta K = 104 - 2 = 102\text{ J}$

**Consistency Check:** $W = 102\text{ J}$ and $\Delta K = 102\text{ J}$. The results are consistent.
