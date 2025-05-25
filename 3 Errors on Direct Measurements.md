### <center>Errors on Direct Measurements</center>

```ad-definition
title:
**Direct measurement** is a measurement in which the result is read directly from the scale of the device.
```

<center><img src="http://urlr.me/fwM7v" alt="" />
</center>


___

*Medical thermometer* : $\Delta_r = \frac{c}{2}$, where $c$ - division rate of the scale
For our thermometer $c = \frac{1}{10}^{\circ}C$, then
$$\Delta = 0.1^{\circ}C + \frac{0.1^{\circ}C}{2} = 0.15^{\circ}C$$
___

#### Errors of electrical measuring devices

$\gamma$ - **accuracy class**, $x_{\max}$ - upper limit of measurement
$$\gamma = \frac{\Delta{x}}{x_{\max}} \cdot 100$$
$$\Delta x = x_{\max}\frac{\gamma}{100}$$

The reference error does not exceed half of the division rate.
$$\Delta_{r} \leq \frac{c}{2},$$
where $c$ - division rate
___


Upper limit of measurement - $u_{max} = 6 \ V$
accuracy class - $\gamma = 4$
result of measurement - $u_o = 4.3 \ V$
division rate of the scale - $c = 0.2 \ V$
device error - $\Delta{u}_d$
relative error - $\varepsilon_u = \frac{\Delta{u}}{u_0}$


$$\Delta{u} = \Delta{u}_d + \frac{c}{2}$$
\
$$\Delta{u}_d = u_{max} \frac{\gamma}{100}$$
$$\Delta{u}_d = 6 \ \text{V} \cdot \frac{4}{100} = 0.24 \ \text{V}$$
$$\Delta{u} = 0.24 \ \text{V}  + \frac{0.2}{2} \ \text{V}  = 0.34 \ \text{V}$$

$$ \varepsilon_u = \frac{\Delta u}{u_o}  \ \ \ \ \ \ \varepsilon_u = \frac{0.34 \ \text{V}}{4.3 \ \text{V}} = 0.079$$

$$u = u_0 \pm \Delta{u} = (4.3 \pm 0.3) \ \text{V}$$
$$\varepsilon_u = 8\%$$
___

####  Weighing errors

Total mass of the weights - $m = 5 \ \text{g} + 2 \cdot 2 \ \text{g} + 20 \ \text{mg} + 10 \ \text{mg} = 9.030 \ \text{g}$
Error of the scales - $\Delta{m}_s = 23 \text{mg}$ (from the tables)
Error of measuring the mass of weights - $\Delta{m}_w = 8 \ \text{mg} +  \ 2 \cdot 6 \ \text{mg} + 1 \ \text{mg} + 1 \ \text{mg} = 22 \ \text{mg}$  (from the tables)
\
$$\Delta{m} = \Delta{m}_s + \Delta{m}_w$$
$$\Delta{m} = 23 \ \text{mg} + 22 \ \text{mg} = 45 \ \text{mg} = 0.045 \ \text{g} \approx 0.05 \ \text{g}$$
\
$$m = (9.03 \ \pm \ 0.05) \ \text{g}$$
\
$$\varepsilon_m = \frac{\Delta{m}}{m} = \frac{0.045 \ \text{g}}{9.030 \ \text{g}} = 4.983 \cdot 10^{-3} \approx 5 \cdot 10^{-3} = 0.005 = 0.5\%$$

___

tags: #measurement #error-theory 

references: [ERRORS ON MEASUREMENT DIRECT MEASUREMENTS](http://jmas.webs.upv.es/ffi/Practices/P0%20Errors/P0%20ERRORS%20ON%20MEASUREMENT_DIRECT%20MEASUREMENTS.pdf)
[Table for Determining the Error of Weighing](http://rl.odessa.ua/media/_For_Liceistu/Physics/Labs_9_klass/Weight_Error.pdf)
[Урок 3. Погрешность прямых измерений](https://www.youtube.com/watch?v=PmAOjwABf-M&list=PL1Us50cZo25n0s1gsVxipdJkc6EQoptM5&index=3)