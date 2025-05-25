### <center>Non-Uniform Circular motion. Tangential Acceleration</center>

What is uniform circular motion? (See [[22 Curvilinear Motion. Uniform Circular Motion. Centripetal Acceleration]])
 
 We know that if we have a point on a rotating object, located at a distance of $r$ from the axis of rotation, then the velocity of thus point is directed tangentially and if the motion is unifrom then:
 
 <center><img src="http://urlr.me/jvPhs" alt=""/></center>

 $v = \omega r$ (for any type of motion)
$\vec{a}_c$ is directed towards the center of the circle
$$a_c = \frac{v^2}{r} \ \ \ \ \ \ \ \ a_c = \omega^2r \ \ \ \ \ \omega = \frac{\varphi}{\Delta t}$$

The formula $a_c = \frac{v^2}{r}$ can be used for any type of motion because it includes only the magnitude of instantaneous velocity at a given moment in time, which means that this acceleration does not depend on what this magnitude was in the previous and in the next instant. Whether it was greater or less, i.e. how the velocity changed. Or maybe it didn't change. The result does not depend on this.

Imagine that the object is moving (rotating) non-uniformly.
<center>Non-Uniform Motion</center>

$$v \neq \text{const.}$$
$$\omega = \frac{v}{r} \ \Rightarrow \ \omega \neq \text{const.}$$
$$\Delta\omega = \omega - \omega_o \ \ \ \ \text{change in angular velocity}$$
$$\large\boxed{\varepsilon = \frac{\omega - \omega_o}{\Delta t} } \ \ \ \ \ \large\boxed{\varepsilon = \frac{\Delta\omega}{\Delta t}} \ \ \ \leftarrow \ \text{Angular Acceleration}$$
For reference $\vec{a} = \frac{\vec{v} - \vec{v}_o}{\Delta t} \ , \ \vec{a} = \frac{\Delta\vec{v}}{\Delta t}$.
$$[\varepsilon] = \frac{\text{rad}}{\text{s}^2} = \frac{1}{\text{s}^2} = \text{s}^{-2}$$

```ad-definition
title:
**Angular acceleration** of an object is a physical quantity equal to the ratio of the change in angular velocity of the object over a short period of time to the duration of that period of time.
```



$$v \neq v_o$$

<center><img src="http://urlr.me/8BbWz" alt=""/></center> 

$$\vec{a} = \frac{\Delta\vec{v}}{\Delta t} \ \ \ \ \ \ \ \ \ \ \ \ \Delta\vec{v} = \vec{v} - \vec{v}_o$$

<center><img src="http://urlr.me/RXFjN" alt=""/></center> 
We are talking about infinitesimal angles. In this case, for example, we can consider an isosceles triangle with two right angles at the base.

$$\Delta\vec{v} = \Delta\vec{v}_r + \Delta\vec{v}_{\tau}$$
$$\Delta\vec{v}_r \neq 0 \ \ \ \ \text{since the motion is} \ \underline{\text{curvilinear}}$$
$$\Delta\vec{v}_{\tau} \neq 0 \ \ \ \ \text{since the motion is} \ \underline{\text{non-uniform}}$$
$$\underbrace{\frac{\Delta\vec{v}}{\Delta t}}_{\large\vec{a}} = \underbrace{\frac{\Delta\vec{v}_r}{\Delta t}}_{\large\vec{a}_r} + \underbrace{\frac{\Delta\vec{v}_{\tau}}{\Delta t}}_{\large\vec{a}_{\tau}}$$
$$\large\vec{a} = \vec{a}_r + \vec{a}_{\tau} \ \ \ \ \ \small(\vec{a_r} \perp \vec{a}_{\tau})$$


$$a_r = \frac{\Delta v_r}{\Delta t} \ \ \ \ \ \ \ \ \frac{\Delta v_r}{v_o} = \Delta\varphi$$
Since $\Delta t \to 0$, we can assume that $\Delta v_r$ equals to the length of the arc, and the angle in radians is measured using the ratio of arc length to radius.
$$a_r = v_o \underbrace{\frac{\Delta\varphi}{\Delta t}}_{\omega} = v_o \omega = \omega r \cdot \omega$$
$\Delta t \to 0$, so the angular velocity as well as the magnitude of linear velocity barely change, $\Delta t \to 0 \ \Rightarrow \ \Delta\varphi \to 0$, so $\omega_o$ is almost equal to $\omega$.
$$\Rightarrow \ a_r = \omega^2r = a_c$$

$$a_{\tau} = \frac{\Delta v_{\tau}}{\Delta t} = \frac{\Delta v}{\Delta t} = \frac{v - v_o}{\Delta t} = \frac{\omega r - \omega_or}{\Delta t}$$
Since $\Delta t \to 0$, $\Delta v$ and $\Delta v_{\tau}$ are almost equal.
$$r \cdot \underbrace{\frac{\omega - \omega_o}{\Delta t}}_{\large\varepsilon} = \varepsilon r$$ 

```ad-definition
title:
If the motion is non-uniform and non-linear, then
$$\vec{a} = \vec{a}_r + \vec{a}_{\tau}$$
$a_r = \omega^2r$, is directed towards the center of the circle
$a_{\tau} = \varepsilon r$, is directed tangentially to the trajectory
```

 <center><img src="http://urlr.me/BD5qw" alt=""/></center>

 $$v \uparrow \ \Rightarrow \ \alpha < 90^{\circ}$$
 
 
  <center><img src="http://urlr.me/5ckyG" alt=""/></center>

 $$v \downarrow \ \Rightarrow \ \alpha > 90^{\circ}$$ 

$$a = \sqrt{a^2_r + a^2_\tau}$$
$$a = \sqrt{(\omega^2r)^2 + (\varepsilon r)^2} \ \ \ \ \to \ \ \ \ \ a = \sqrt{(\frac{v^2}{r})^2 + (\frac{\Delta v}{\Delta t})^2} $$


If we imagine that a straight line is a circle with an infinite radius, then the ratio of the square of the velocity to the radius will tend to zero and we get the well-known formula for acceleration, $a = \frac{\Delta v}{\Delta t}$.

---

tags: #motion #mechanics/kinematics #curvilinear-motion 


references: [Урок 47. Неравномерное движение по окружности. Тангенциальное ускорение](https://www.youtube.com/watch?v=-D_Ihv1hTR8)


