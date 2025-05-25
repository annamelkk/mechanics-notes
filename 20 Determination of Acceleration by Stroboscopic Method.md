### <center>Determination of Acceleration by Stroboscopic Method</center>



<center><img src="http://urlr.me/DqXQs" alt=""/></center> 

$\tau$ - time intervals between stroboscope flashes.

We have to express $a$ in terms of quantities we can measure.
$$v_{\text{avg}_1} = \frac{S_1}{\tau} \ \ \ \ \ \ \ \ v_{\text{avg}_2} = \frac{S_2}{\tau}$$

$$v_{\text{avg}_1} = \frac{v_1 + v_2}{2} \ (1) \ \ \ \ \ \ \ \ v_{\text{avg}_2} = \frac{v_2 + v_3}{2} \ (2)$$
$$(2)-(1)$$ $$ v_{\text{avg}_2} - v_{\text{avg}_1} = \frac{v_2 + v_3}{2} - \frac{v_1 + v_2}{2} = \frac{v_2 + v_3 - v_1 - v_2 }{2}$$

On the other hand
$$ v_{\text{avg}_2} - v_{\text{avg}_1} = \frac{S_2}{\tau} - \frac{S_1}{\tau} = \frac{S_2 - S_1}{\tau} $$

\
$$\frac{ v_3 - v_1 }{2} = \frac{S_2 - S_1}{\tau} \ \ \ \ \ \ \  v_3 - v_1 = \frac{2 (S_2 - S_1)}{\tau}$$ $$a = \frac{v_3 - v_1}{2\tau}$$
$2\tau$ passed after the magnitude of velocity changed from $v_1 \to v_3$.

$$a = \frac{2 (S_2 - S_1)}{\tau} \cdot \frac{1}{2\tau} = \frac{S_2 - S_1}{\tau^2} $$
$$\boxed{a = \frac{ S_{ \text{next} } - S_{  \text{previous} } }{\tau^2} }$$


---

$\large\boxed{ \text{Experiment}}$
![[20 strobe.png]]
The ruler is placed VERTICALLY.
Quantities we have to measure:
Flash frequency in the stroboscope $\nu = 30\frac{\text{flash}}{ \text{sec}}$ (device characteristics)
$x$, cm - the coordinate that changes along the ruler
$S$, cm - displacement
$S_{ \text{next} } - S_{  \text{previous}}$

<center><img src="http://urlr.me/b6nFM" alt=""/></center>

$$S_{ \text{next} } - S_{  \text{previous}} = 1.1 \cdot 10^{-2} \ \text{m}$$
$$\tau = \frac{1}{\nu} \ \ \ \ \ \boxed{a = (S_{ \text{next} } - S_{  \text{previous}})\nu^2} $$
$$a = 1.1 \cdot 10^{-2} \ \text{m} \cdot 900 \frac{1}{\text{s}^2} = 9.9 \frac{\text{m}}{\text{s}^2}$$

---
This method is one of the simplest, but when using it, the result has a large error.
Let's remember from [[4 Errors on Indirect Measurements]]
  If $f = x-y$, then $\Delta f = \Delta x + \Delta y$, $\varepsilon = \frac{\Delta f}{f_o} = \frac{\Delta x + \Delta y}{x_o - y_o}$.
  It is not good to construct an experimental method based on the calculation of close values.
  ---
  
  tags: #measurement #motion #mechanics/kinematics 
  
  references: [Урок 36. Измерение ускорения стробоскопическим методом](https://www.youtube.com/watch?v=kOBTqHhJCl4&list=PL1Us50cZo25k6lXqOyfCYiKoTvaSbYxHX&index=13)

