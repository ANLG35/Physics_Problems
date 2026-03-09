# Mathematical and Physical Analysis

## 3. Path Intersection
**Problem:** Alice moves at $A(t) = (2+t, 8-3t)$ and Bob at $B(t) = (2t-1, 2t+2)$. Determine if they collide.

### Solution
1. **Collision Condition:** Set $A(t) = B(t)$ for the same time $t$.
   * $x: 2 + t = 2t - 1 \implies t = 3$
   * $y: 8 - 3t = 2t + 2 \implies 5t = 6 \implies t = 1.2$
2. **Conclusion:** Since the times do not match, they do not collide.
3. **Minimum Distance:** Define distance $D(t) = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}$.
   * Minimize $f(t) = D^2(t) = (t-3)^2 + (5t-6)^2 = 26t^2 - 66t + 45$.
   * Set $f'(t) = 52t - 66 = 0 \implies t \approx 1.27$.


---

## 4. Rearranging Formulas
**Problem:** Solve $T = 2\pi \sqrt{\frac{L}{g}}$ for $g$.

### Solution
1. $\frac{T}{2\pi} = \sqrt{\frac{L}{g}}$
2. $\left(\frac{T}{2\pi}\right)^2 = \frac{L}{g} \implies \frac{T^2}{4\pi^2} = \frac{L}{g}$
3. $g = \frac{4\pi^2 L}{T^2}$

---

## 5. Trigonometry
**Problem:** Vector magnitude 15, angle $60^\circ$.

### Solution
* **Horizontal Component:** $15 \cos(60^\circ) = 15 \times 0.5 = 7.5$.
* **Vertical Component:** $15 \sin(60^\circ) = 15 \times \frac{\sqrt{3}}{2} \approx 12.99$.


---

## 6. Function Analysis
**Problem:** $f(x) = 3x^2 - 12x + 7$.

### Solution
1. **Find Critical Points:** $f'(x) = 6x - 12$. Set $f'(x) = 0 \implies x = 2$.
2. **Classify:** $f''(x) = 6 > 0$. Therefore, $x=2$ is a local minimum.

---

## 7. Logic & Series
**Problem:** Fly between 10m apart bike (1m/s) and wall.

### Solution
* Bike hits wall at $t = 10\text{m} / 1\text{m/s} = 10\text{s}$.
* Fly travels at $2\text{m/s}$ for $10\text{s}$: $2 \times 10 = 20\text{ meters}$.

---

## 8. Definite Integrals
**Problem:** $\int_{0}^{\pi} \sin(x) \, dx$.

### Solution
* $[-\cos(x)]_{0}^{\pi} = (-\cos(\pi)) - (-\cos(0)) = 1 - (-1) = 2$.
