Let $n_1$ and $n_2$ be the sample size of the two groups.  
$T_1$ represents the sum of the ranks for the first sample when all observations are ranked from smallest to largest.  
$T_1^*$ represents the sum of the ranks for the first sample when all observations are ranked from largest to smallest.  
Because $T_1$ and $T_1^\*$ both have $n_1$ observations, they also have $n_1$ ranks.  
The number of all observations is ($n_1+n_2$).  
$T_1 = r_1 + r_2 + r_3 + ... + r_{n_1}$  
Therefore

$$
T_1^\* = (n_1 + n_2 -r_1 +1) +(n_1 + n_2 -r_2 +1) + (n_1 + n_2 -r_3 +1) + ... + (n_1 + n_2 -r_{n_1} +1) 
$$ 

$$
T_1^\* = n_1 * (n_1 + n_2 +1) - (r_1 + r_2 + r_3 + ... + r_{n_1})
$$ 

$$
T_1^\* = n_1 * (n_1 + n_2 +1) - T_1
$$ 
