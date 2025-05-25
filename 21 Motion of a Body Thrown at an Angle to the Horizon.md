### <center>Motion of an Object Thrown at an Angle to the Horizon</center>

$$\large\vec{a} = \vec{g}$$ 
$$\vec{S} = \vec{v}_ot + \frac{\vec{g}t^2}{2}$$
$$\vec{v} = \vec{v}_o + \vec{g}t$$

$\underline{\text{Given}: v_o \ \ \alpha}$
$1.$Flight time $t_f \ - ?$
$2.$Maximum lifting height of the object $h \ - ?$
$3.$Flight range$L \ - ?$
$4.$Trajectory equation $y(x) \ - ?$

<center><img src="http://urlr.me/hMnYR" alt=""/></center>
<center><img src="http://urlr.me/GNCM1" alt=""/></center>

---

$\large1.$ Flight time $t_f$
$$y(t_f) = 0$$
From $(2) \ \ \ \ \ \ \ \ \ \ \large v_o\sin\alpha\cdot t_f - \frac{gt_f^2}{2} = 0$ 
- $t_f = 0$ when we just threw the object its height is also zero.
- Consider $t_f>0$ $$v_o\sin\alpha\cdot t_f - \frac{gt_f^2}{2} = 0$$ $$v_o\sin\alpha = \frac{gt_f}{2}$$ $$\large\boxed{t_f = \frac{2v_o\sin\alpha}{g}}$$
	- $t_f \sim v_o$
	- $t_f = \max$, when $\alpha = 90^{\circ}$

---

$\large2.$ The maximum lifting height of the object $h$
When $y=h \ \ \to \ \ v_y=0$
From $(4) \ \ \ \ \ \ \ \ \ \ \large 0=v_o\sin\alpha - gt_1$ 
$t_1$ - time taken to reach the highest point
$$t_1 = \frac{v_o\sin\alpha}{g}$$ $$h=y(t)$$
\
From $(2)$
$$\large\begin{align}
h = v_o\sin\alpha \cdot t_1 - \frac{g}{2}t_1^2 \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \\
=v_o\sin\alpha \frac{v_o\sin\alpha}{g} - \frac{g}{2}\frac{v_o^2\sin^2\alpha}{g^2} \ \ \ \ \ \ \ \\ 
= \frac{v_o^2\sin^2\alpha}{g} - \frac{v_o^2\sin^2\alpha}{2g} = \frac{v_o^2\sin^2\alpha}{2g}
\end{align}
$$
$$\large\boxed{h = \frac{v_o^2\sin^2\alpha}{2g} }$$

- $h \sim v_o^2$
- $h = \max$, when $\alpha = 90^{\circ}$

---
$\large3$  Flight range $L$

$$L = x(t_f)$$

From $(1) \Rightarrow$
$$\begin{align}
L = v_o\cos\alpha \cdot t_f \ \ \ \ \ \ \ \ \ \ \ \ \ \\
 = v_o\cos\alpha \cdot \frac{2v_o\sin\alpha}{g} 
\end{align}
$$

<center><img src="http://urlr.me/h37fM" alt=""/></center>

$$\large\boxed{L = \frac{v_o^2 \cdot \sin2\alpha}{g}}$$

- $L \sim v_o^2$
- $L = \max$ when $\alpha = 45^{\circ}$

Let 's say $\alpha$ is equal to some value
1. Throwing angle $\alpha$
2. Throwing angle $\beta = 90^{\circ} - \alpha$

$$\begin{align}
L = \frac{v_{o}^{2} \cdot 2\sin \beta \cos \beta }{g} = \frac{v_{o}^{2} \cdot 2\sin(90^{\circ} - \alpha )\cos(90^{\circ} - \alpha )}{g} \\
=\frac{v_{o}^{2} \cdot 2\sin \alpha \cos \alpha }{g} = L \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \
\end{align}
$$

That is, if we throw the object at an angle of $\alpha$ it will fly the same distance as if we threw it at an angle of $90^{\circ} - \alpha$.

---

$\large4.$Trajectory equation $y(x)$

From $(1) \ \ \ \large t = \frac{x}{v_o\cos\alpha} \ \ \to (2)$

$$y = v_o\sin\alpha \frac{x}{v_o\cos\alpha} - \frac{g}{2}\frac{x^2}{v_o^2\cos^2\alpha}$$

$$\large y = \underbrace{-\frac{g}{2v_o^2\cos^2\alpha}}_a \cdot x^2 + \underbrace{\tan\alpha}_b \cdot x$$
<center>Trajectory equation </center>

Remember $y = ax^2 + bx + c$
The graph will be a <font color="#A394CA"> parabola</font>, the branches of which are directed downwards and which passes through the origin.

<center><img src="http://urlr.me/w9PFz" alt=""/></center>

<center><font color="#7d8b8b"> The larger α, the smaller the cosine, the larger the sine</font></center>

- Maximal flight distance is at $45^{\circ}$
- If we throw the body twice with angles one $\alpha$ and the other $90^{\circ}-\alpha$, that is, at angles the sum of which is $90^{\circ}$, then the flight range will be less than at $45^{\circ}$, but it will be the same.

<center>Stricter Graph</center>

$v_o$ is the same

<center><img src="http://urlr.me/CSPFK" alt=""/></center>

---

What we are considering is very simplified.
Remember that the rotation of the earth, the presence of air, the fact that the earth is round, the fact that the density of atmospheric air decreases with increasing altitude were not taken into account, we also assume that $\vec{g}=\overrightarrow{\text{const.}}$ and it does not depend on the height and horizontal coordinates.


$\boxed{ \text{Ballistics}}$ - field of mechanics concerned with the launching, flight behavior and impact effects of projectiles.


<center><img src="http://urlr.me/Ymcv1" alt=""/></center>



<center>Ballistic Curve</center>

---


tags: #motion #mechanics/kinematics 



references: [Ballistics ](https://en.wikipedia.org/wiki/Ballistics)
[Урок 38. Движение тела,брошенного под углом к горизонту (окончание)](https://www.youtube.com/watch?v=A-D2C7eBtto&list=PL1Us50cZo25k6lXqOyfCYiKoTvaSbYxHX&index=15)


