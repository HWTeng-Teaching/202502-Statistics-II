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
