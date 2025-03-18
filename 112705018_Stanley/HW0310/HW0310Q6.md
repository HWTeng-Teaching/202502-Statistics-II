## Q6
When using rule of thumb to check if two variances are the same, approximate the significance level with $n_1 = 4$ and $n_2 = 3$.

## Solution to Q6

Rule of Thumb : If $\frac{larger s^2}{smaller s^2} \leq 3$, the equal variance assumption is reasonable.

The significance $\alpha = P(F_{n_{1}-1, n_{2}-1} > 3) + P(F_{n_{1}-1, n_{2}-1} < \frac{1}{3}) = P(F_{3, 2} > 3) + P(F_{3, 2} < \frac{1}{3}) \approx 0.25993 + 0.19245 = 0.45238$ (calculated in Python)
