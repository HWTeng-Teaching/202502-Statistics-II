## C12S04Q05
<img width="400" alt="img" src="https://github.com/user-attachments/assets/1e24a86f-f41d-431d-b6bc-e291d56fdc15/">

In the normal probability plot, all the datas scatter around the regression line. That's the evidence that the regression assumption does not be violated.

In the residuals versus fits plot, we see that residuals do not randomly scatter around $y=0$. The equal variance assumption is violated.

## C12S04Q08
<img width="400" alt="img" src="https://github.com/user-attachments/assets/feaeafae-32d5-4172-b71d-201ce58d0ea0"/>
<br>
<img width="400" alt="img" src="https://github.com/user-attachments/assets/192d6771-3607-40dc-82a1-6e12b46ab9f5"/>

**a.**

(1) Exists a linear relationship between variable x and the dependent variable y. $y = \alpha + \beta x + \epsilon$  
(2) The values of random error term $\epsilon$ are independent.  
(3) $The random error ~ N(0,\sigma^2)$.  
(4) The random errors are normally distributed.

**b.**\
As shown in the table, the best estimate of $\sigma^2$ is $58.05$.

**c.**\
In the normal probability plot, the residuals are showing normality. Valid is the normal distribution assumption.
In the residuals versus fits plot, there are residueals that do not scatter randomly around y = 0. It violates the assumption of equal variances.
## C12S04Q09

<img width="200" alt="img" src="https://github.com/user-attachments/assets/cd4e0919-e252-4f7e-a6ce-f74c472677c3/">
<img width="200" alt="img" src="https://github.com/user-attachments/assets/c2a024dc-ddc5-4df1-9513-a48201d52b23/">
<img width="200" alt="img" src="https://github.com/user-attachments/assets/bdf1c2b8-b874-41fd-ab73-63e7a017d730/">

**a.**\
Only 2.7% of the variation in TV price is explained by screen size, indicating a weak realtionship.

**b.**\
In the normal probability plot, the residuals closely follow the straight line. In the residuals versus fitted value plot, there is non-constant spread of residuals which indicates violation of equal variance assumption.

The variance assumptions appears violated.

**c.**\
![image](https://github.com/user-attachments/assets/07cebaef-312b-4dcd-8a22-90e91288e42d)

We see no clear relation between price and size. Therefore the assumption of linearity is violated.
## C12S05Q12
<img width="400" alt="img" src="https://github.com/user-attachments/assets/b742261b-6520-4995-97ae-a12520d0f389"/>

**a.**\
$\hat{y} = a+bx$\
$b = \frac{S_xy}{S_xx} = \frac{\sum{xy}-\frac{\sum{x} \sum{y}}{n}}{\sum{x^2} -\frac{(\sum{x})^2}{n}} = 1.5$\
$a = \bar{y} - b \bar{x} = 4.3$

Least-squares regression line: $\hat{y}=4.3+1.5x$

**b.**\
![image](https://github.com/user-attachments/assets/3cf35bdb-d005-4d8b-9df9-d47e334d3aa1)

**c.**\
$TSS = S_{yy} = \sum y^2 - \frac{(\sum y)^2}{n} = 1204 - \frac{132^2}{15} = 42.4$\
$SSR = \frac{S_{xy}^2}{Syy} = \frac{42.4^2}{1204} = 1.4932$\
$SSE = 42.4 - 1.4932 = 40.9068$\
$s^2 = MSE = \frac{SSE}{n-2} = \frac{40.9068}{13} = 3.1467$

**d.**\
ANOVA table:

| Source | df | SS | MS | F |
|:------|:------|:------|:------|:------|
| Regression | 1 | 1.4932 | 1.4932 | 0.4745 |
| Error | 13 | 40.9068 | 3.1467 |  |
| Total | 14 | 42.4 |  |  |

$H_0: \quad b = 0, H_a: \quad b \neq 0$\
$\alpha = 0.05$

$F_{STAT} = \frac{MSR}{MSE} \sim F_{1,n-2}$\
$F_{1,13} = \frac{MSR}{MSE} = \frac{1.4932}{3.1467} = 0.4745$

critical value: $F_{1,13,0.05} = 4.6672$

$4.6672 > 0.4745$, therefore we don't reject $H_0$ and say there is no sufficient evidence to indicate that the length of decision time is linearly related to the number of alternative package designs

**e.**\
$p-value = P(F>0.4745) = 0.5030$, thus we don't reject $H_0$ as in the previous sector.

**f.**\
![image](https://github.com/user-attachments/assets/eeed83cf-64ef-4f5d-ab07-e175fb520e8c)
![image](https://github.com/user-attachments/assets/180ede77-41c4-4804-a39d-ccb2b12de837)

**g.**\
95%CI: $\hat{y} \pm t_{n-2, \alpha/2} \times \sqrt{MSE \times (\frac{1}{n} + \frac{(x_0-\bar{x})^2}{S_{xx}})}
= 8.8 \pm t_{13, 0.025} \times \sqrt{3.1467 \times (\frac{1}{15} + \frac{(3-3)^2}{10})}
= 8.8 \pm 2.16 \times \sqrt{3.1467 \times \frac{1}{15}}
= (7.8107, 9.7893)$

## C12S05Q15

<img width="400" alt="image" src=https://github.com/user-attachments/assets/61ff0854-08b9-4fbe-aff0-92634afb93ac/>

**a.**\
$\hat{y} = a + bx$  

$S_{xy} = \sum xy - \frac{\sum x \sum y}{n}= -14 - \frac{0 \times 10}{5} = -14$\
$S_{xx} = \sum x^2 - \frac{(\sum x)^2}{n}= 16 - \frac{0^2}{5} = 16$

$b = \frac{S_{xy}}{S_{xx}} = \frac{-147}{16} = -0.875$\
$a = \bar{y} - b\bar{x} = 2$

least-squares regression line: $\hat{y} = 2 - 0.875x$  

$SSE = TSS - SSR = S_{yy} - \frac{S_{xy}^2}{Syy} = 12.5 - \frac{(-14)^2}{16} = 0.25$\
$MSE = \frac{SSE}{n-2} = \frac{0.25}{3} = 0.0833$

$\hat{y} = 2 - 0.875 \times (-1) = 2.875$  

99% CI: $\hat{y} \pm t_{n-2, \alpha/2} \times \sqrt{MSE \times (\frac{1}{n} + \frac{(x_0-\bar{x})^2}{S_{xx}})}
= 2.875 \pm t_{3, 0.005} \times \sqrt{0.0833 \times (\frac{1}{5} + \frac{(-1-0)^2}{16})}
= 2.875 \pm 5.841 \times \sqrt{0.0833 \times (\frac{1}{5} + \frac{1}{16})}
= (2.0113, 3.7387)$

**b.**\
$\hat{y} = 2 - 0.875 \times 1 = 1.125$  

95% PI: $\hat{y} \pm t_{n-2, \alpha/2} \times \sqrt{MSE \times (1 + \frac{1}{n} + \frac{(x_0-\bar{x})^2}{S_{xx}})}
= 2.875 \pm t_{3, 0.025} \times \sqrt{0.0833 \times (1 + \frac{1}{5} + \frac{(-1-0)^2}{16})}
= 2.875 \pm 5.841 \times \sqrt{0.0833 \times (\frac{1}{5} + \frac{1}{16})}
= (2.0113, 3.7387)$

**c.**\
The width of PI: $(\hat{y} + t_{n-2, \alpha/2} \times \sqrt{MSE \times (1 + \frac{1}{n} + \frac{(x_0-\bar{x})^2}{S_{xx}})}) 
-(\hat{y} - t_{n-2, \alpha/2} \times \sqrt{MSE \times (1 + \frac{1}{n} + \frac{(x_0-\bar{x})^2}{S_{xx}})})= 2 \times t_{n-2, \alpha/2} \times \sqrt{MSE \times (1 + \frac{1}{n} + \frac{(x_0-\bar{x})^2}{S_{xx}})}
= 2 \times t_{n-2, \alpha/2} \times \sqrt{MSE \times (1 + \frac{1}{5} + \frac{x_0^2}{16})}$

Thus, for the width of PI to be minimun, $x$ should be 0.
## C12S05Q18
<img width="600" alt="img" src=https://github.com/user-attachments/assets/ae6537c1-951e-48e6-a8c2-28da615d9dfb/>

**a.**
[Code](https://colab.research.google.com/drive/1T_WxMZXH9CYbe7u58Rf_r-Eb6VBs2W0d?usp=sharing)

![image](https://github.com/user-attachments/assets/54efc361-5fac-4fe7-8cf6-621d8c156613)

We can observe a positive correlation between phosphorus applied to the soil and phosphorus present in the plant, and some variability within the same X.

**b.**
$$\bar{x}=0.2834, \bar{y}=157.5834$$

Let the best fitting line be $\hat{y} =  a + bx$

$b = \frac{SXY}{SXX} = \frac{88.4667}{0.3267} = 270.82$

$a = \bar{y}-b\bar{x} =  80.85$

Least-squares line: $\hat{y} = 80.9 + 270.8x$ 

![image](https://github.com/user-attachments/assets/5a53233d-12c3-4ba2-b6ca-f506415ae612)

**c.**

$H_0: \quad b = 0$

$H_a: \quad b \neq 0$  

$\alpha = 0.05$

$\because p-value = 0.003 < 0.05$  

$\therefore reject \quad H_0$  

The data provide sufficient evidence of a linear relationship

**d.**

By the table it provided

90% CI: $(112.130, 157.900)$

$t^* = t_{n-2,0.1} = t_{10,0.1} = 1.812$

$x_0 = 0.20$

$SE_{\hat{y}} = s \cdot \sqrt{ \frac{1}{n} + \frac{(x_0 - \bar{x})^2}{\sum (x_i - \bar{x})^2} } = 12.6264$

$s=\sqrt{\frac{\sum (y_i - \hat{y_i})^2}{n-2}} = 39.04190$

$CI=\hat{y}(x_0)\pm t^* \cdot SE_\hat{y} = 135.01531\pm 1.812 \cdot 12.6264 = (112.130, 157.900)$

## C12S06Q13
<img width="400" alt="image" src=https://github.com/user-attachments/assets/139d6076-6903-42d2-9c51-50a40208138f>

Average drill hole depth as independent variable x, and average temperature as dependent variable y  

$S_{xy} = \sum xy - \frac{\sum x \sum y}{n}= 1,901,500 - \frac{8050 \times 2100}{9} = 23166.67$\
$S_{xx} = \sum x^2 - \frac{(\sum x)^2}{n}= 602222.22$\
$S_{yy} = \sum y^2 - \frac{(\sum y)^2}{n}= 8200$

$r = \frac{S_{xy}}{\sqrt{S_{xx}S_{yy}}} = \frac{23166.67}{\sqrt{60222.22 \times 8200}} =0.3297$

$H_0: \quad \rho = 0, H_a: \quad \rho > 0$\
$\alpha = 0.05$

$t_{STAT} = r \times \sqrt{\frac{n-2}{1-r^2}} \sim t_{n-2}$\
$t^* = 0.3297 \times \sqrt{\frac{7}{1-0.3297^2}} = 0.9240$

critical value: $t_{7,0.05} = 1.895$

$0.9249<1.895$, therefore we do not reject $H_0$ and say there is no significant positive correlation between average maximum drill hole depth and average maximum temperature.

## C12S06Q14
<img width="400" alt="image" src=https://github.com/user-attachments/assets/d4b31c24-235e-4483-a19e-f7887ccc6676>
