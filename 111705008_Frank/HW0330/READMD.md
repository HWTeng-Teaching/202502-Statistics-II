## C11S01Q8,9,14

![image](https://github.com/user-attachments/assets/5eb17de7-fe39-48df-80f5-4a2cb273049d)

![image](https://github.com/user-attachments/assets/7e7b4570-7e58-44a5-b49a-2bc1c26b860e)

![image](https://github.com/user-attachments/assets/1135d0a0-70eb-473a-96f8-c4c0dafad2eb)

## Solution of 8
FActor: type of fertilizer
Levels: 3
## Solution of 9
Factor: Daily doses of vitamin C
Levels: 3
## Solution of 14
By CTL, this is binomial distribution $bin~X(100,p)$, and may be a normal distribution.

## C11S02Q10
![image](https://github.com/user-attachments/assets/64e6c932-ba49-4d46-9900-e3adefd0f4cb)

![image](https://github.com/user-attachments/assets/c70cf92e-d3a0-48a0-919f-f9e806d1e0be)
![image](Q2.JPG)
## C11S02Q14
<img width="400" alt="image" src="https://github.com/user-attachments/assets/45d83f92-f5ed-4477-85b5-fed45fda7e16" /><br>
<img width="400" alt="image" src="https://github.com/user-attachments/assets/269c1e27-905d-48b8-9408-35d68f7fbe52" />
![image](Q3.1.JPG)
![image](Q3.2.JPG)
## C11S02Q8
<img width="400" alt="image" src="https://github.com/user-attachments/assets/fa148a5f-c720-4153-985e-f0ee10d6f18e" />

![image](Q4.JPG)

## C11S03Q16
<img width="400" alt="image" src="https://github.com/user-attachments/assets/49f1d3ad-cdb3-4979-ad51-5fa2f79b13ad" />

$$
\omega = q_{\alpha}(k, N-k) \times \sqrt{\frac{MSE}{n_t}}
= q_{0.01}(4, 16) \times \sqrt{\frac{41.25}{5}}
= 5.19 \times \sqrt{\frac{41.25}{5}}
= 14.907
$$

$\bar{x_2}$ differes from otehr means, as its difference with $\bar{x_3}$ exceeds $\omega$

## C11S03Q17
<img width="400" alt="image" src="https://github.com/user-attachments/assets/f175430a-b80d-477e-b58c-24dc45dae722" /><br>
<img width="400" alt="image" src="https://github.com/user-attachments/assets/3bc7dd32-6bd2-4f70-85e9-62127b7bca6a" />

**a.**\
$H_0: \quad \mu_1 = \mu_2 = \mu_3, H_a: \quad \exists \mu_i \neq \mu_j, i \neq j$\
$a = 0.05$\
$X_{LS} = X_{1\cdot} = 6080 \quad X_{PS} = X_{2\cdot} = 6530 \quad X_{SS} = X_{3\cdot} = 5320$\
$X_{\cdot\cdot} = 17930$\
$N = 30$\  
$k = 3$\

$CM = \frac{X_{\cdot\cdot}^2}{N} = \frac{17930^2}{30} = 10716163.33$

$TSS = \sum_{i=1}^{k} \sum_{j=1}^{n_i} x_{ij}^2 -CM = 11016900 - 10716163.33 = 300736.67$

$SST = \sum_{i=1}^{k} \sum_{j=1}^{n_i} (\bar{x_{i\cdot}} - \bar{x_{\cdot\cdot}})^2 = \sum_{i=1}^{k} \frac{x_{i\cdot}^2}{n_i} -CM = 10790970 - 10716163.33 = 74806.67$

$SSE = TSS - SST = 300736.67 - 74806.67 = 225930$

ANOVA Table

| Source | df | SS | MS | F |
|:------|:------|:------|:------|:------|
| Treatment | 2 | 74806.67 | 37403.335 | 4.47 |
| Error | 27 | 225930 | 8367.778 |  |
| Total | 29 | 300736.67 |  |  |

Critical value: $F_{2,27,0.05} = 3.35$\
$4.47 > 3.35$, therefore we reject $H_0$ sand say there is sufficient evidence to indicate a difference in the maean GRE scores for applicants admitted to the three programs

**b.**
$95% cI$: $\bar{x_{1\cdot}} - \bar{x_{2\cdot}} \pm t_{N-k, \alpha/2} \times \sqrt{MSE \times (\frac{1}{n_1}+\frac{1}{n_2})}
= \bar{x_{1\cdot}} - \bar{x_{2\cdot}} \pm t_{27, 0.025} \times \sqrt{MSE \times (\frac{1}{10}+\frac{1}{10})}
= 608 - 653 \pm 2.052 \times \sqrt{8367.78 \times (\frac{1}{10}+\frac{1}{10})}
= (-128.9455, 38.9455)$

**c.**\
$\omega = q_{\alpha}(k, N-k) \times \sqrt{\frac{MSE}{n_t}}
= q_{0.05}(3, 27) \times \sqrt{\frac{8367.78}{10}}
= 3.506 \times \sqrt{\frac{8367.78}{10}}
= 101.4185$

$\bar{X_3.}$
## C11S04Q24,25
<img width="400" alt="image" src="https://github.com/user-attachments/assets/4c0faafd-d56f-4c5f-bd00-7b868b647304" /><br>
<img width="400" alt="image" src="https://github.com/user-attachments/assets/bce76f90-d5f7-4515-9cdc-2ecb691bd650" />

## C11S04Q26
<img width="400" alt="image" src="https://github.com/user-attachments/assets/2bc6fb39-f31c-44bc-bef1-d7df8337bba7" /><br>
<img width="500" alt="image" src="https://github.com/user-attachments/assets/923c8241-b0e1-4ba0-adab-5e56c0347536" />

