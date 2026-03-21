## Problem: Velocity and Acceleration Vectors

**Given:** The position vector of an object is:  
$$\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$$

### 1. Velocity Vector $\vec{v}(t)$
Velocity is the first derivative of the position vector with respect to time $t$:  
$$\vec{v}(t) = \frac{d\vec{r}}{dt}$$

Differentiating each component:  
* $\frac{d}{dt}(3t^2) = 6t$
* $\frac{d}{dt}(5t - 8t^2) = 5 - 16t$

**Result:** $$\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}$$

---

### 2. Acceleration Vector $\vec{a}(t)$
Acceleration is the derivative of the velocity vector with respect to time $t$:  
$$\vec{a}(t) = \frac{d\vec{v}}{dt}$$

Differentiating each component:  
* $\frac{d}{dt}(6t) = 6$
* $\frac{d}{dt}(5 - 16t) = -16$

**Result:** $$\vec{a}(t) = 6\hat{i} - 16\hat{j}$$
