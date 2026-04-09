# Physics Report: Conservation of Momentum

## 1. Problem Description
A runner jumps onto a stationary cart. We need to determine the final velocity of the combined system and verify if kinetic energy is conserved during this interaction.

### System Parameters
| Parameter | Symbol | Value |
| :--- | :--- | :--- |
| Mass of Runner | $m_r$ | 70 kg |
| Initial Velocity of Runner | $v_r$ | 3 m/s |
| Mass of Cart | $m_c$ | 140 kg |
| Initial Velocity of Cart | $v_c$ | 0 m/s |

---

## 2. Calculation of Final Velocity ($v_f$)
Based on the **Law of Conservation of Momentum**, the total momentum before the jump must equal the total momentum after the jump.



[Image of conservation of momentum in an inelastic collision]


$$P_{initial} = P_{final}$$
$$m_r v_r + m_c v_c = (m_r + m_c) v_f$$

**Plug in the values:**
$$(70 \times 3) + (140 \times 0) = (70 + 140) \times v_f$$
$$210 = 210 \times v_f$$
$$v_f = 1 \text{ m/s}$$

**Result:** The final velocity of the cart and runner is **1 m/s**.

---

## 3. Kinetic Energy Analysis
To determine if kinetic energy is conserved, we compare the energy levels before and after the collision.

### Initial Kinetic Energy ($KE_i$)
$$KE_i = \frac{1}{2} m_r v_r^2 = \frac{1}{2} (70)(3)^2 = 315 \text{ J}$$

### Final Kinetic Energy ($KE_f$)
$$KE_f = \frac{1}{2} (m_r + m_c) v_f^2 = \frac{1}{2} (210)(1)^2 = 105 \text{ J}$$

### Conclusion
Since $KE_i (315 \text{ J}) \neq KE_f (105 \text{ J})$, **kinetic energy is NOT conserved**. This is a **perfectly inelastic collision** where 210 J of energy was converted into heat, sound, and internal work.
