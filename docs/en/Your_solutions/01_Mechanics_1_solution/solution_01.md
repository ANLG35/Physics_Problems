# Solutions goes here
# 1. Projectile Motion Analysis

**Problem Statement:**
A projectile is fired with an initial velocity $v_0 = 100 \, \text{m/s}$ at an angle $\theta = 37^\circ$ above the horizontal. Assume $g \approx 9.8 \, \text{m/s}^2$ and no air resistance.

---

### A. Differential Equations of Motion
The motion is governed by constant acceleration:
* **Horizontal:** $\ddot{x} = 0 \implies v_x(t) = v_0 \cos\theta$
* **Vertical:** $\ddot{y} = -g \implies v_y(t) = v_0 \sin\theta - gt$

### B. Kinematic Determinations
Using the initial components:
* $v_{0x} = 100 \cos(37^\circ) \approx 79.86 \, \text{m/s}$
* $v_{0y} = 100 \sin(37^\circ) \approx 60.18 \, \text{m/s}$

1. **Time of Flight ($T$):** Set $y(t) = 0$
   $$T = \frac{2 v_0 \sin\theta}{g} = \frac{2 \cdot 60.18}{9.8} \approx 12.28 \, \text{s}$$

2. **Maximum Height ($H$):** Set $v_y = 0$
   $$H = \frac{(v_0 \sin\theta)^2}{2g} = \frac{60.18^2}{2 \cdot 9.8} \approx 184.82 \, \text{m}$$

3. **Range ($R$):** $R = v_x \cdot T$
   $$R = 79.86 \cdot 12.28 \approx 980.68 \, \text{m}$$

---

...
