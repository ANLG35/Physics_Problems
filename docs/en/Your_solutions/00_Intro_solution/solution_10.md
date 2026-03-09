# Section 0: Mathematical Foundations

## 10. Infinite Series

**Problem:** An ant starts at $(0,0)$ and follows a pattern of movements: 
$1$ m East, $1/2$ m North, $1/3$ m West, $1/4$ m South, $1/5$ m East, and so on. 
Determine the final $(x, y)$ position.

---

### Solution

The movement can be broken down into $x$ (East-West) and $y$ (North-South) components.

**1. x-coordinate (East-West):**
The sequence is: $+1 - 1/3 + 1/5 - 1/7 + \dots$
This is the Taylor series for the arctangent function: $\arctan(x) = x - x^3/3 + x^5/5 - x^7/7 + \dots$
For $x=1$: $\arctan(1) = 1 - 1/3 + 1/5 - 1/7 + \dots = \pi/4$

**2. y-coordinate (North-South):**
The sequence is: $+1/2 - 1/4 + 1/6 - 1/8 + \dots$
Factor out $1/2$: $1/2 \cdot (1 - 1/2 + 1/3 - 1/4 + \dots)$
This is the Taylor series for the natural logarithm: $\ln(1+x) = x - x^2/2 + x^3/3 - x^4/4 + \dots$
For $x=1$: $\ln(2) = 1 - 1/2 + 1/3 - 1/4 + \dots$
So, the y-coordinate is: $1/2 \cdot \ln(2)$

> **Final Position:** $(\pi/4, \frac{\ln(2)}{2}) \approx (0.785, 0.347)$

---
