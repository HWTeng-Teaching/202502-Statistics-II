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

$S^2=\frac{(n_1-1) S_1^2 + (n_2-1) S_2^2}{n_1+n_2-2}$

$\left( \frac{(n - 1) S^2}{\chi^2_{\alpha / 2, n - 1}}, \frac{(n - 1) S^2}{\chi^2_{1 - \alpha / 2, n - 1}} \right) = \left( \frac{15 \times 21.07}{27.49}, \frac{15 \times 21.07}{6.26} \right) = (11.5, 50.49)$

Thus, the CI is (11.5, 50.49).

### c. 

Construct a 95% CI for Variance and Standard Deviation of Yards per Pass:

Using the chi-square distribution,

$$
\left( \frac{(n - 1) S_y^2}{\chi^2_{\alpha / 2, n - 1}}, \frac{(n - 1) S_y^2}{\chi^2_{1 - \alpha / 2, n - 1}} \right) = \left( \frac{15 \times 6.4}{27.49}, \frac{15 \times 6.4}{6.26} \right) = (3.49, 15.34)
$$

Thus, the CI is (3.49, 15.34).

For standard deviation:

$$
\left( \sqrt{3.49}, \sqrt{15.34} \right) = (1.87, 3.92)
$$

### d.

Define: $\sigma$ as the standard deviation of yards per pass.

Hypothesis Test:

$$
H_0: \sigma = 4
$$
$$
H_a: \sigma \neq 4
$$
$$
\text{set } \alpha = 0.05
$$

Test statistic:

Since the sample size is $n = 16$, we use the chi-square test for variance,

$$
\chi ^ 2 = \frac{(n - 1) S^2}{\sigma_0^2}
$$

The sample variance is

$$
S^2 = (2.53)^2 = 6.4
$$

Calculating,

$$
\chi^2 = \frac{(16 - 1) \times 6.4}{4^2} = \frac{15 \times 6.4}{16} = 6
$$

The p-value for a two-tailed test is

$$
p = 2 \times \min \left( P(\chi ^ 2_{15} > 6), P(\chi ^ 2_{15} < 6) \right) = 0.04
$$

Since 0.04 < 0.05, we reject $H_0$.

Therefore, we reject the null hypothesis and conclude that the standard deviation of yards per pass is significantly different from 4.

## C10S05Q13
![image](https://github.com/user-attachments/assets/66c7696a-15cd-4f30-ae1f-d3d13275a48b)

## C10S06Q14
![image](https://github.com/user-attachments/assets/618c6142-0194-4b39-b807-8555b2291d5c)

![image](https://github.com/user-attachments/assets/8950149f-7f78-4aca-8eb1-7c6ac493ad7b)
## C10S06Q16
![image](https://github.com/user-attachments/assets/a2049937-93ba-487d-8ff2-83a5651f83df)

## C10S06Q22
![image](https://github.com/user-attachments/assets/698ff020-856c-4f34-a82c-2a225be23bc4)
