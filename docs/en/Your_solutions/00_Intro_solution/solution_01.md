# Section 0: Mathematical Foundations

## 1. Vector Algebra

We are given two vectors in $\mathbb{R}^3$:
$$\vec{a} = [2, 1, -3], \quad \vec{b} = [4, -2, 1]$$

---

### Necessary Definitions and Formulas

1. **Magnitude (Length) of a vector:**
   For $\vec{v} = [v_x, v_y, v_z]$, the magnitude is $|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}$

2. **Dot Product:**
   $\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z$

3. **Cross Product:**
   $\vec{a} \times \vec{b} = [a_y b_z - a_z b_y, \quad a_z b_x - a_x b_z, \quad a_x b_y - a_y b_x]$

4. **Angle between two vectors:**
   $\theta = \arccos\left(\frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}\right)$

---

### (a) Magnitude of Each Vector

**Magnitude of $\vec{a}$:**
$$|\vec{a}| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{4 + 1 + 9} = \sqrt{14}$$

**Magnitude of $\vec{b}$:**
$$|\vec{b}| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{16 + 4 + 1} = \sqrt{21}$$

> **Result (a):** $|\vec{a}| = \sqrt{14}, \quad |\vec{b}| = \sqrt{21}$

---

### (b) Dot Product $\vec{a} \cdot \vec{b}$

Compute component-by-component:
$$\vec{a} \cdot \vec{b} = (2)(4) + (1)(-2) + (-3)(1)$$
$$\vec{a} \cdot \vec{b} = 8 - 2 - 3 = 3$$

> **Result (b):** $\vec{a} \cdot \vec{b} = 3$

---

### (c) Cross Product $\vec{a} \times \vec{b}$



Using the determinant expansion for $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$:

* **x-component:** $(1)(1) - (-3)(-2) = 1 - 6 = -5$
* **y-component:** $(-3)(4) - (2)(1) = -12 - 2 = -14$
* **z-component:** $(2)(-2) - (1)(4) = -4 - 4 = -8$

> **Result (c):** $\vec{a} \times \vec{b} = [-5, -14, -8]$

---

### (d) Angle Between $\vec{a}$ and $\vec{b}$

Using the geometric definition:
$$\theta = \arccos\left(\frac{3}{\sqrt{14} \cdot \sqrt{21}}\right) = \arccos\left(\frac{3}{\sqrt{294}}\right)$$

**Numerical Approximation:**
$$\sqrt{294} \approx 17.146 \implies \frac{3}{17.146} \approx 0.175$$
$$\theta \approx \arccos(0.175) \approx 79.9^\circ$$

> **Result (d):** $\theta \approx 79.9^\circ$

---

### Final Summary Table

| Operation | Calculated Result |
| :--- | :--- |
| **Magnitudes** | $|\vec{a}| = \sqrt{14}, \quad |\vec{b}| = \sqrt{21}$ |
| **Dot Product** | $3$ |
| **Cross Product** | $[-5, -14, -8]$ |
| **Angle ($\theta$)** | $\approx 79.9^\circ$ |
