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
