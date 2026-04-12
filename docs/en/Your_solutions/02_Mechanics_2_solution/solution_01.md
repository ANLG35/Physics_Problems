# Physics Problem: Period and Length of a Simple Pendulum

## Part 1: Pendulum Period on the Moon
**Problem:** A simple pendulum has a period of 4 seconds on Earth. What would be its period on the Moon, where gravity is approximately 1/6 of Earth's gravity?

**Solution:**
The period $T$ of a simple pendulum is given by the formula:
$$T = 2\pi \sqrt{\frac{L}{g}}$$

Given:
* $T_{Earth} = 4\text{ s}$
* $g_{Moon} = \frac{1}{6}g_{Earth}$

Since $T \propto \frac{1}{\sqrt{g}}$, we can set up a ratio:
$$\frac{T_{Moon}}{T_{Earth}} = \sqrt{\frac{g_{Earth}}{g_{Moon}}}$$
$$\frac{T_{Moon}}{4} = \sqrt{\frac{g_{Earth}}{\frac{1}{6}g_{Earth}}} = \sqrt{6}$$
$$T_{Moon} = 4\sqrt{6} \approx 9.80\text{ s}$$

---

## Part 2: Required Length for a 1-Second Period
**Problem:** What is the required length for a simple pendulum to have a period of exactly 1 second on Earth?

**Solution:**
Using the period formula and solving for $L$:
$$T = 2\pi \sqrt{\frac{L}{g}} \implies L = g \left( \frac{T}{2\pi} \right)^2$$

Given:
* $T = 1\text{ s}$
* $g \approx 9.81\text{ m/s}^2$

$$L = 9.81 \times \left( \frac{1}{2\pi} \right)^2$$
$$L = \frac{9.81}{4\pi^2} \approx \frac{9.81}{39.478}$$
**$L \approx 0.248\text{ meters}$ (or $24.8\text{ cm}$)**
