### <center>Measurement Accuracy</center>

<center>
	<img src="http://urlr.me/KtkGf" alt="" />
</center>

$l = 0.3852 \ \text{m}$ - here the number of *significant figures* stays the same: there are still four significant digits here.
And although zero is a digit, it is not a significant digit. The zeros on the left are not significant.

$l = 385.2 \ \text{mm}$ - there are still four significant digits here.

$l = 385200 \ \mu\text{m}$ - here the number of significant figures is also four. It is agreed that the zeros on the right are significant, but in this situation it should be somehow noted that they are insignificant because they do not contain any information about accuracy in them. Then, we can rewrite this expression as $l = 3.852 \cdot 10^5 \ \mu\text{m}$.  Or we can denote the first insignificant zero as shown:

<center><img src="http://urlr.me/fSzbx" alt="
" /></center>

___

##### Uncertainty

The uncertainty with which the number is depicted is half the unit of the lowest digit - for the number $38.52 \ \text{cm}$, the accuracy is $\pm 0.005 \ \text{cm}$.

The physical quantity $l$ can vary within the range of $38.515 \ \text{cm} < l < 38.525 \ \text{cm}$.

###### How to find the uncertainty of measurement?
** <center>
	Classification of Errors by Origin
	</center>**

- **Random Errors** -  the effect of unpredictable factors.
- **Systematic Errors**  - incorrect usage of instruments or imperfect method of measurement.
	- _Instrumental Errors_ - instrumental errors are attributed to imperfections in the tools with which the experimenter works.
	- _Method Errors_ - this type of errors many times occur when you do not consider how to control an experiment.
- **Personal Errors** - these errors are the result of ignorance, carelessness, prejudices, or physical limitations of the experimenter.
___
**<center> Classification of Errors by Meaning </center>**

```ad-definition
title:
**Absolute Error**  is the difference between the actual value of a physical quantity and the result of its measurement. 
```

<center ><img src="http://urlr.me/W281j" alt="" /></center>
	

*The Absolute Error Limit* ($\Delta{x}$) - The limit of absolute error is the maximum possible value of the absolute error. 
  $$\Delta{x} = |x - x_o|_{\max}$$
  
 <center><img src="http://urlr.me/95Kjq" alt="" /></center>

---
 
 Length of the table $95 \ \text{cm} \ \ \ \ \Delta x = 1 \ \text{cm}$
 $$94 \ \text{cm} \ < \ l \ < \ 96 \ \text{cm}$$
 
Thickness of the table top  $2 \ \text{cm} \ \ \ \ \Delta x = 1 \ \text{cm}$
 $$1 \ \text{cm} \ < \ h \ < \ 3 \ \text{cm}$$
 
 The same absolute error limit actually indicates that the second result is of unacceptable uncertainty, while the first result is fairly acceptable.
 
---

```ad-definition
title:
**Relative error**  ($\varepsilon$) is the ratio of the *absolute error limit* to the measurement result.
$$\varepsilon_x = \frac{\Delta{x}}{x_o}$$
```

---

#### <center>Rules for Rounding Measurements</center>

- The absolute error limit is rounded to one significant digit.
	- **Exception**: If this number is 1 then rounding is performed to two significant digits.
		- on the calculator - $\Delta{x} = 3.848491611$, we write $\Delta x = 4$
- The number of significant digits in the result should be such that the uncertain figure has the order of the absolute error limit.
	- on the calculator - $x = 384.811 \ 645$, we write $x = 385$
		- $x = 385 \pm 4$
- The absolute error is rounded to one significant digit.
	- **Exception**: see $\uparrow$




____

tags: #measurement #error-theory 

references: [Richelieu Lyceum Error Theory](http://www.rl.odessa.ua/media/_For_Liceistu/Physics/Labs_9_klass/Err_Theory.pdf)
[Урок 2. Точность физических величин](https://www.youtube.com/watch?v=AlKy1Oc0x-U&list=PL1Us50cZo25n0s1gsVxipdJkc6EQoptM5&index=2)