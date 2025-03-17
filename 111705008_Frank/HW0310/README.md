## C10S05Q12
![image](https://github.com/user-attachments/assets/8a3b763e-b5cc-49d5-b076-a7c732ab6004)
![image](https://github.com/user-attachments/assets/f7d92974-7d23-4f09-bdf3-a5a9e90a0a84)
#### a.
Completions\
$\bar{x} = \frac{\sum x_i}{n} = \frac{350}{16} = 21.25$

$S_x = \sqrt{\frac{\sum (x_i - \bar{x})^2}{n - 1}} = 2.316$

Yards per pass\
$\bar{y} = \frac{\sum y_i}{n} = \frac{207.8}{16} = 12.99$

$S_y = \sqrt{\frac{\sum (y_i - \bar{y})^2}{n - 1}} = 2.52$

#### b.

Construct a 95% CI for Variance of Completions:

Using the chi-square distribution,

$\left( \frac{(n - 1) S^2}{\chi^2_{\alpha / 2, n - 1}}, \frac{(n - 1) S^2}{\chi^2_{1 - \alpha / 2, n - 1}} \right) = \left( \frac{15 \times 5.36}{27.49}, \frac{15 \times 5.36}{6.26} \right) = (2.29, 12.84)$

Thus, the CI is $(2.29, 12.84)$.

#### c. 

Construct a 95% CI for Variance and Standard Deviation of Yards per Pass:

Using the chi-square distribution,

$\left( \frac{(n - 1) S_y^2}{\chi^2_{\alpha / 2, n - 1}}, \frac{(n - 1) S_y^2}{\chi^2_{1 - \alpha / 2, n - 1}} \right) = \left( \frac{15 \times 6.35}{27.49}, \frac{15 \times 6.35}{6.26} \right) = (3.46, 15.22)$

Thus, the CI for variance is $(3.46, 15.22)$.

For standard deviation:

$\left( \sqrt{3.46}, \sqrt{15.22} \right) = (1.86, 3.90)$

#### d.
$H_0: \sigma_0 = 4$

$H_a: \sigma_0 \neq 4$

$\text{set } \alpha = 0.05$

Test statistic and its sampling distribution:

$\chi^2_{STAT} = \frac{(n - 1) S^2}{\sigma_0^2}\sim \chi^2_{n-1}$

Test statistic:

$\chi ^ 2 = \frac{(n - 1) S^2}{\sigma_0^2}=\frac{15 \times 2.52^2}{16} =5.95$

The critical value is $\chi_{15;0.025}^2 = 27.4884$ or $\chi_{15;0.975}^2 = 6.26214$

The rejection region is { $\chi^2$: $\chi^2>27.4884$ or $\chi^2 < 6.26214$}

Since $5.95<6.26214$, we reject $H_0$ and say there is sufficient evidence to show that the standard deviation of the yards per pass for this quarterback differs from $\sigma = 4$.

## C10S05Q13
![image](https://github.com/user-attachments/assets/66c7696a-15cd-4f30-ae1f-d3d13275a48b)
#### a

$H_0: \sigma_0 = 0.7$

$H_a: \sigma_0 > 0.7$

$\bar{x} = \frac{353+351+351+355}{4}=352.5$

$S^2= \frac{353^2+351^2+351^2+355^2-4 \times 352.5^2}{3}= \frac{11}{3} \approx 3.6667$

$s = \sqrt{3.6667} \approx 1.915$

$\chi^2 = \frac{(n-1) s^2}{\sigma_0^2}$  

$\chi^2 = \frac{(4-1)(3.6667)}{0.7^2}=\frac{3 \times 3.667}{0.49}=\frac{11.001}{0.49} \approx 22.45$

Critical value: $\chi_0.05,3 =7.815$

Since $22.45 > 7.815$, we reject $H_0$ and say the variance is significantly greater than 7.815.

#### b

Confidence interval: $(\frac{(n-1)S^2}{\chi^2_upper},\frac{(n-1)S^2}{\chi^2_lower})$

**Calcutlate the 90% CI**

$CI = (\frac{(3)(3.667)}{7.815},\frac{(3)(3.667)}{0.352}) = (\frac{11.001}{7.815},\frac{11.001}{0.352}) = (1.408,31.253)$


## C10S06Q14
![image](https://github.com/user-attachments/assets/618c6142-0194-4b39-b807-8555b2291d5c)

![image](https://github.com/user-attachments/assets/8950149f-7f78-4aca-8eb1-7c6ac493ad7b)
## C10S06Q16
![image](https://github.com/user-attachments/assets/a2049937-93ba-487d-8ff2-83a5651f83df)

## C10S06Q22
![image](https://github.com/user-attachments/assets/698ff020-856c-4f34-a82c-2a225be23bc4)
