## Why is the correlation coefficient $r$ always between $[-1, 1]$?

### Definition
The sample correlation coefficient is defined as:

$$
r = \frac{S_{xy}}{\sqrt{S_{xx} S_{yy}}}
$$

Where:
- $S_{xy}$: sample covariance
- $S_{xx}, S_{yy}$: sample variances of $x$ and $y$

### Key Idea
By the **Cauchy–Schwarz Inequality**, we have:

$$
S_{xy}^2 \leq S_{xx} \cdot S_{yy}
$$

Dividing both sides by $S_{xx} S_{yy}$:

$$
\frac{S_{xy}^2}{S_{xx} S_{yy}} \leq 1
\Rightarrow r^2 \leq 1
\Rightarrow |r| \leq 1
\Rightarrow r \in [-1, 1]
$$

### Conclusion
Therefore, the correlation coefficient $r$ must lie within the interval $[-1, 1]$:
- $r = 1$: perfect positive linear relationship
- $r = -1$: perfect negative linear relationship
- $r = 0$: no linear relationship
