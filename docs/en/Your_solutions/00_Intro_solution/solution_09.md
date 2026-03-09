# Section 0: Mathematical Foundations

## 9. Optimization Problem

**Problem:** A rectangle is inscribed under the curve $y = 3 - x^2$ in the first quadrant. Find the dimensions $(x, y)$ that maximize the area of this rectangle.

---

### Mathematical Derivation

1. **Define the Area Function:**
   The width of the rectangle is $x$ and the height is $y = 3 - x^2$.
   $$A(x) = \text{width} \cdot \text{height} = x(3 - x^2)$$
   $$A(x) = 3x - x^3$$

2. **Find the Critical Points:**
   To maximize the area, find the first derivative and set it to zero:
   $$A'(x) = \frac{d}{dx}(3x - x^3) = 3 - 3x^2$$
   $$3 - 3x^2 = 0 \implies x^2 = 1 \implies x = 1 \quad (\text{since } x > 0 \text{ in Q1})$$

3. **Calculate Corresponding Height:**
   Substitute $x = 1$ into the curve equation:
   $$y = 3 - (1)^2 = 2$$

4. **Verify Maximum (Second Derivative Test):**
   $$A''(x) = -6x$$
   $$A''(1) = -6 < 0 \implies \text{Confirmed local maximum.}$$

> **Conclusion:** The dimensions for the maximum area are **width = 1** and **height = 2**.

---
