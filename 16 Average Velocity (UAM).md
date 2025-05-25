What are [[12 Average Velocity, Speed]]?

---

### <center>Average Velocity in Uniformly Accelerated Motion</center>


$$\large\vec{v}_{\text{avg}} = \frac{ \vec{S} }{t}  \ \ \ \ \ \ \ (1)$$

For Uniformly Accelerated Motion:

$$
\large\begin{rcases*}
S_x = v_{o_x}t + \frac{ a_xt }{2} \\
S_y = v_{o_y}t + \frac{ a_yt }{2} \\
S_z = v_{o_z}t + \frac{ a_zt }{2}
\end{rcases*} \ \ \rightarrow \ \ \ \boxed{ \vec{S} = \vec{v}_ot + \frac{\vec{a}t^2}{2} }
$$

$v_{o_{(x/y/z)}}$ - projection of the initial velocity
$a_{(x/y/z)}$ - projection of the acceleration

If we substitute into $(1)$ the equation we derived for $\vec{S}$, we get 
$$\vec{v}_{\text{avg}} = \frac{ \vec{v}_ot + \frac{\vec{a}t^2}{2} }{t} = \vec{v}_o + \frac{\vec{a}t}{2}$$

Now, we know that $\vec{v} = \vec{v}_o + \vec{a}t$, then $\vec{a}t = \vec{v} - \vec{v}_o$, thus
$$\vec{v}_{\text{avg} } = \vec{v}_o + \frac{  \vec{v} - \vec{v}_o }{2} = \underline{\vec{v}_o} + \frac{\vec{v}}{2} - \underline{\frac{\vec{v}_o}{2} }= \frac{\vec{v}}{2} + \frac{\vec{v}_o}{2} $$

$$\large\boxed{\vec{v}_{\text{avg}} = \frac{\vec{v} + \vec{v}_o}{2} }$$

**<center>Average Velocity in Uniformly Accelerated Motion</center>
**

```ad-highlight
title:
In uniformly accelerated motion, the average velocity of the body is equal to **the arithmetic mean** of the initial and final velocities.
```

We know that $\vec{S} = \vec{v}_{\text{avg}} \cdot t$, from the equation above we get
 
 $$\large\boxed{ \vec{S} = \frac{ \vec{v} + \vec{v}_o }{2} \cdot t }$$
 
 For comparison take a look at $\vec{S} = \vec{v}_ot + \frac{\vec{a}t^2}{2}$.
 
 
 $$\large\boxed{\vec{v}_{\text{avg}} = \frac{\vec{v} + \vec{v}_o}{2} } \ \ \ \ \ \ \ \ \large\boxed{ \vec{S} = \frac{ \vec{v} + \vec{v}_o }{2} \cdot t } $$
 
 ---
 
 <center><img src="http://urlr.me/db5WB" alt=""/></center>

 ```ad-highlight
 title:
 In uniformly accelerated motion, the instantaneous velocity of the body coincides with the average velocity **in the middle of the time interval** in which the motion of the body is considered.
 ```
 
 ---
 
 
 ```ad-highlight
 title:
 In uniformly accelerated motion without initial velocity, **"the law of odd numbers" is held**: the distances traveled by the body in consecutive equal intervals of time are related as consecutive numbers: $$ s_1 : s_2 :  \ ... \ : s_n = 1 : 3 : \ ... \ : (2n-1)$$
 ```
 
To prove this statement, first let's label some quantities:
$v_o = 0$ (as stated)
$\tau$ - time interval size

<center><img src="http://urlr.me/trKV5" alt=""/></center>


 $$S = \underbrace{v_ot}_{=0} + \frac{at^2}{2}$$
 $$S_n = \frac{ a(n\tau)^2 }{2} - \frac{ a((n-1)\tau)^2 }{2} = \frac{a\tau^2}{2} (n^2 - (n-1)^2) = \frac{a\tau^2}{2}(n^2-n^2+2n-1)$$
 $$S_n = \frac{a\tau^2}{2}(2n-1)$$

<div style="text-align: right"> qed. </div>

 
 
 
*<center>Geometrical Proof</center>*
<center><img src="http://urlr.me/2BJzk" alt=""/></center>

---

tags: #motion #velocity #mechanics/kinematics 

references: [Урок 27. Средняя скорость при РУД ](https://www.youtube.com/watch?v=rp-igVufp-U&list=PL1Us50cZo25k6lXqOyfCYiKoTvaSbYxHX&index=4)
 
 
 