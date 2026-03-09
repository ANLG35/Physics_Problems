# 8. Definite Integrals

**Problem:** Calculate the area under the curve of the function $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$.

---

### Solution

To find the area under the curve of $f(x)$ from $a$ to $b$, we evaluate the definite integral:
$$\text{Area} = \int_{0}^{\pi} \sin(x) \, dx$$

1. **Find the antiderivative:**
   The antiderivative of $\sin(x)$ is $-\cos(x)$.

2. **Apply the Fundamental Theorem of Calculus:**
   $$\int_{0}^{\pi} \sin(x) \, dx = [-\cos(x)]_{0}^{\pi}$$

3. **Evaluate at the boundaries:**
   $$\text{Area} = (-\cos(\pi)) - (-\cos(0))$$

4. **Calculate the result:**
   Since $\cos(\pi) = -1$ and $\cos(0) = 1$:
   $$\text{Area} = (-(-1)) - (-1)$$
   $$\text{Area} = 1 + 1$$
   $$\text{Area} = 2$$

> **Conclusion:** The area under the curve of $f(x) = \sin(x)$ from $x = 0$ to $x = \pi$ is **2** square units.

---
