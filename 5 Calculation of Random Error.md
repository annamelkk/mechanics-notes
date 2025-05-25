### <center>Calculation of Random Error</center>

Let's say we are measuring some physical quantity which we will denote by $x$. If we take several measurements we get what is called a *series of results of measurements*.

$$\large \text{Series of results of $N$ measurements}$$ $$\large x_1 , x_2 , ... , x_N$$
- Result of Measurements - average (mean) value
	- $$x_o = \overline{x} = \frac{x_1 + x_2 + ... + x_N}{N} \ \ \ \ \text{or} \ \  \ \ \ \overline{x} = \frac{\sum_{i = 1}^{N}x_i}{N}$$
- We determine the **standard deviation ($\sigma$)** 
	- $$\sigma = \sqrt{\frac{ ( x_1 - \overline{x} )^2 + ( x_2 - \overline{x} )^2 + ... + ( x_N - \overline{x} )^2 }{N-1}} \ \ \ \ \  \text{or} \ \  \ \ \  \sigma = \sqrt{\frac{ \sum_{i = 1}^{N} (x_i - \overline{x})^2 }{N-1}}$$
	- It turns out that if we take another measurement, it will lie in the interval $\large \overline{x} - 3\sigma < x_{N+1} < \overline{x} + 3\sigma$ with a probability of 997 chances out of 1000.
- We determine absolute error limit of $\overline{x}$
	- $$\Delta x = \frac{3\sigma}{\sqrt{N}}$$
- As a result, the answer will look like this $$x = \overline{x} \pm \Delta x$$ $$\varepsilon = \frac{\Delta x}{\overline{x}}$$

___
##### Example
$l \ \ \ \ \ \ \ \ 250 \ \text{cm}, \ 240 \ \text{cm}, \ 262 \ \text{cm}, \ 248 \ \text{cm}, \ 260 \ \text{cm}$
$N = 5$
 $${\overline{l} = \frac{1}{N} \sum_{i = 1}^{N}l_i} \ \ \ \ \ \ \ {\sigma = \sqrt{\frac{ \sum_{i = 1}^{N} (l_i - \overline{l})^2 }{N-1}}} \ \ \ \ \ \ \ {\Delta l = \frac{3\sigma}{\sqrt{N}}} $$
 
 
| $N$ (In order) | $l,\ \ \text{cm}$ | $\overline{l}, \ \ \text{cm}$ | $\lvert{l - \overline{l}}\rvert, \ \ \text{cm}$ | $(l - \overline{l})^2, \ \ \text{cm}^2$ | $\sigma, \ \ \text{cm}$ | $\Delta l, \ \ \text{cm}$ |     |
| -------------- | ----------------- | ----------------------------- | ----------------------------------------------- | --------------------------------------- | ----------------------- | ------------------------- | 
| 1              | $$250$$           |                               | $$3$$                                           | $$9$$                                   |                         |                           |     |
| 2              | $$245$$           |                               | $$8$$                                           | $$64$$                                  |                         |                           |     |
| 3              | $$262$$           | $$253.0$$                     | $$9$$                                           | $$81$$                                  | $$7.55$$                | $$10.13$$                 |     |
| 4              | $$248$$           |                               | $$5$$                                           | $$25$$                                  |                         |                           |     |
| 5              | $$260$$           |                               | $$7$$                                           | $$49$$                                  |                         |                           |     |
|                | $$\sum = 1265$$   |                               |                                                 | $$\sum = 228$$                          |                         |                           |     |

$$\varepsilon = \frac{10.13 \ \text{cm}}{253.0 \ \text{cm}} = 0.0400$$
\
$$\text{ANSWER:} \ \ \ \ l = (253 \pm 10) \text{cm}; \ \ \ \ \varepsilon= 4\%$$

<center><img src="http://urlr.me/QjvMR" alt="" /></center>

___

##### In general

$$\large \Delta = \Delta_d + \Delta_{ref} + \Delta_r,$$
where $\Delta_d$ - device error
$\Delta_{ref}$ - reference error
$\Delta_r$ - random error
But if we are dealing with reality, then many of these quantities can simply be discarded.

___

$$\Delta x = \frac{3\sigma}{\sqrt{N}}$$
If $N = 9$, then $$\Delta x = \frac{3\sigma}{\sqrt{9}} = \sigma$$

___

tags: #measurement #error-theory 


references: [Урок 5. Вычисление случайной погрешности](https://www.youtube.com/watch?v=mrBLA93wZb4&list=PL1Us50cZo25n0s1gsVxipdJkc6EQoptM5&index=5)
