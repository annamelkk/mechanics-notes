### <center>Errors on Indirect Measurements</center>

```ad-definition
title:
**Indirect measurement** is a measurement whose result is calculated using a formula in which the results of direct measurements are substituted.
```

<center><img src="http://urlr.me/kDpFP" alt="" /></center>

___

Let us measure indirectly some quantity $f$, while in the formula we will substitute two other quantities, which we will denote by $x$ and $y$.

- *<u>Error of the sum and difference.</u>* 
	-	Let $f = x + y \ \ \ \ \text{or} \ \ \ \ f = x - y$,  then $$\large \boxed{\Delta{f} = \Delta{x} + \Delta{y} }$$
	- The absolute error of the sum or difference of two quantities is equal to  the sum of the absolute errors of these quantities.
	- Relative error:$$\varepsilon_f = \frac{\Delta{f}}{f_0}  = \frac{\Delta{x} + \Delta{y}}{x_0 \pm y_0}$$
- *<u>Error of the product and quotient.</u>*
	- Let $f = x \cdot y \ \ \ \ \text{or} \ \ \ \  f = \frac{x}{y}$,  then $$\large \boxed{ \varepsilon_{f} = \varepsilon_{x} + \varepsilon_{y} }$$
	
	- Relative error of the product or quotient of two quantities is equal to the sum of the relative errors of these quantities.
	- $$\varepsilon_{f} = \frac{\Delta f}{f_0}$$ $$\large \underline{\Delta f = \varepsilon_{f} \cdot f_0}$$
	- *Special case*
		- Let $f = x^2 \Rightarrow  \ \ f = x \cdot x, \ \ \ \ \ \varepsilon_{f} = \varepsilon_{x} + \varepsilon_{x} = 2\varepsilon_{x}$,  thus $$\large f = x^n \ \ \Rightarrow \ \ \underline{ \varepsilon_{f} = n\cdot \varepsilon_{x}}$$
		- From this proof follows that $f = \sqrt[n]{x} \ \ \Rightarrow \ \ \underline{ \varepsilon_{f} = \frac{\varepsilon_{x}}{n} }$



___

tags: #measurement #error-theory 


references: [Урок 4. Погрешность косвенных измерений](https://www.youtube.com/watch?v=n8IgntrRc2s&list=PL1Us50cZo25n0s1gsVxipdJkc6EQoptM5&index=4)