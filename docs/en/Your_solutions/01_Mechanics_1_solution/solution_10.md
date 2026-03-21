## Problem: Kinematics of Point M (3D Helical Motion)

**Given:** The position vector of point M is:
$$\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)$$
where $a, b, \omega$ are positive constants.

---

### a) Finding the Trajectory Equation
The trajectory is defined by the coordinates:
* $x = a \cos(\omega t)$
* $y = b \sin(\omega t)$
* $z = bt \implies t = \frac{z}{b}$

To find the relationship between $x$ and $y$, we isolate the trigonometric terms:
$$\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = \cos^2(\omega t) + \sin^2(\omega t) = 1$$

**Result:** The trajectory is an **Elliptical Helix**. Its projection on the $xy$-plane is an ellipse:
$$\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$$

---

### b) Path Length from $t=0$ to $t=t_0$
The path length $s$ is the integral of the speed $|\vec{v}(t)|$:
$$\vec{v}(t) = \frac{d\vec{r}}{dt} = (-a\omega \sin(\omega t), b\omega \cos(\omega t), b)$$
$$|\vec{v}(t)| = \sqrt{(-a\omega \sin(\omega t))^2 + (b\omega \cos(\omega t))^2 + b^2}$$
$$|\vec{v}(t)| = \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}$$

The path length is:
$$s = \int_{0}^{t_0} \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2} \, dt$$

*Special Case:* If $a=b$, then $|\vec{v}| = \sqrt{b^2\omega^2 + b^2} = b\sqrt{\omega^2+1}$, and $s = b t_0 \sqrt{\omega^2+1}$.

---

### c) Discussion of Special Cases
1.  **Circular Helix ($a=b$):** If $a$ and $b$ (in the $x,y$ components) were equal, the projection on the $xy$-plane would be a circle.
2.  **Straight Line ($a=0, b=0$):** Not possible here as constants are positive, but as $\omega \to 0$, the motion becomes purely linear along the $z$-axis.
