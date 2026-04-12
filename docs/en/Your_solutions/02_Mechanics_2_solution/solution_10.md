# Physics Problem: Kinematics and Dynamics of a Particle

## Problem Statement
In a certain force field, the equations of motion of a particle with mass $m = 0.5\text{ kg}$ are given by:
* $x(t) = 5t^2 - t$
* $y(t) = 2t^3$
* $z(t) = -3t + 2$

Find the time dependence of the particle's velocity ($\vec{v}$), momentum ($\vec{p}$), acceleration ($\vec{a}$), the force acting on it ($\vec{F}$), and the power transferred by the field ($P$).

---

## Solution

We start by expressing the position vector $\vec{r}(t)$ using unit vectors $\hat{i}$, $\hat{j}$, and $\hat{k}$:
$$\vec{r}(t) = (5t^2 - t)\hat{i} + (2t^3)\hat{j} + (-3t + 2)\hat{k}$$

### 1. Velocity ($\vec{v}$)
Velocity is the first derivative of the position vector with respect to time ($\vec{v} = \frac{d\vec{r}}{dt}$):
* $v_x = \frac{d}{dt}(5t^2 - t) = 10t - 1$
* $v_y = \frac{d}{dt}(2t^3) = 6t^2$
* $v_z = \frac{d}{dt}(-3t + 2) = -3$

**$$\vec{v}(t) = (10t - 1)\hat{i} + (6t^2)\hat{j} - 3\hat{k}$$**

### 2. Momentum ($\vec{p}$)
Momentum is the product of mass and velocity ($\vec{p} = m\vec{v}$). Given $m = 0.5\text{ kg}$:
$$\vec{p}(t) = 0.5 \times \left[ (10t - 1)\hat{i} + (6t^2)\hat{j} - 3\hat{k} \right]$$

**$$\vec{p}(t) = (5t - 0.5)\hat{i} + (3t^2)\hat{j} - 1.5\hat{k}$$**

### 3. Acceleration ($\vec{a}$)
Acceleration is the derivative of velocity with respect to time ($\vec{a} = \frac{d\vec{v}}{dt}$):
* $a_x = \frac{d}{dt}(10t - 1) = 10$
* $a_y = \frac{d}{dt}(6t^2) = 12t$
* $a_z = \frac{d}{dt}(-3) = 0$

**$$\vec{a}(t) = 10\hat{i} + 12t\hat{j}$$**

### 4. Force ($\vec{F}$)
According to Newton's Second Law ($\vec{F} = m\vec{a}$):
$$\vec{F}(t) = 0.5 \times (10\hat{i} + 12t\hat{j})$$

**$$\vec{F}(t) = 5\hat{i} + 6t\hat{j}$$**

### 5. Power ($P$)
Power transferred by the force field is the dot product of Force and Velocity ($P = \vec{F} \cdot \vec{v}$):
$$P(t) = (F_x \cdot v_x) + (F_y \cdot v_y) + (F_z \cdot v_z)$$
$$P(t) = \left[ 5 \times (10t - 1) \right] + \left[ 6t \times 6t^2 \right] + \left[ 0 \times (-3) \right]$$
$$P(t) = (50t - 5) + 36t^3 + 0$$

**$$P(t) = 36t^3 + 50t - 5\text{ Watts}$$**
