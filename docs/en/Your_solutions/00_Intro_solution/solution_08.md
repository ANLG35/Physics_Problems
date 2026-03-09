# Section 0: Mathematical Foundations

## 1. Vector Algebra

**Given:** $\vec{a} = [2, 1, -3]$, $\vec{b} = [4, -2, 1]$

### (a) Magnitude of each vector
$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx 3.74$
$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx 4.58$

### (b) Dot product $\vec{a} \cdot \vec{b}$
$\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1) = 8 - 2 - 3 = 3$

### (c) Cross product $\vec{a} \times \vec{b}$
$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$
$= \mathbf{i}(1 - 6) - \mathbf{j}(2 - (-12)) + \mathbf{k}(-4 - 4) = [-5, -14, -8]$

### (d) Angle between $\vec{a}$ and $\vec{b}$
$\cos \theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}||\vec{b}|} = \frac{3}{\sqrt{14}\sqrt{21}} = \frac{3}{\sqrt{294}}$
$\theta = \arccos\left(\frac{3}{\sqrt{294}}\right) \approx 79.9^\circ$

---

## 8. Definite Integrals

**Calculate:** $\int_{0}^{\pi} \sin(x) \, dx$

### Solution
1. **Find the antiderivative:** The integral of $\sin(x)$ is $-\cos(x)$.
2. **Apply fundamental theorem of calculus:**
   $$\int_{0}^{\pi} \sin(x) \, dx = [-\cos(x)]_{0}^{\pi}$$
   $$= (-\cos(\pi)) - (-\cos(0))$$
   $$= (-(-1)) - (-1)$$
   $$= 1 + 1 = 2$$

> **Answer:** The area under the curve is **2** square units.

---
