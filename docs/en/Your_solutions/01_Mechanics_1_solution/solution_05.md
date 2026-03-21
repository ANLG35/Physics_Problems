## Problem: Relative Velocity (Crossing a River)

**Given:**
* River velocity ($\vec{v}_r$): $2\text{ m/s}$ (East)
* Boat velocity in still water ($v_b$): $5\text{ m/s}$
* River width ($d$): $200\text{ meters}$
* Goal: Travel directly North.

### 1. Determining the Direction (Angle)
To travel directly North, the boat must head at an angle $\theta$ **West of North** to counteract the eastward river current. The eastward component of the boat's velocity must equal the river's speed.

$$\sin(\theta) = \frac{v_{river}}{v_{boat}}$$
$$\sin(\theta) = \frac{2}{5} = 0.4$$
$$\theta = \arcsin(0.4) \approx 23.58^\circ$$

**Result:** The boat should head approximately **$23.58^\circ$ West of North**.

---

### 2. Time to Cross the River
The velocity component of the boat directed straight North ($v_y$) is:
$$v_y = \sqrt{v_{boat}^2 - v_{river}^2}$$
$$v_y = \sqrt{5^2 - 2^2} = \sqrt{25 - 4} = \sqrt{21} \approx 4.58\text{ m/s}$$

The time ($t$) required to cross is:
$$t = \frac{\text{width}}{v_y} = \frac{200}{\sqrt{21}}$$
$$t \approx \frac{200}{4.58} \approx 43.64\text{ seconds}$$

**Result:** It will take approximately **$43.64$ seconds** to cross.
