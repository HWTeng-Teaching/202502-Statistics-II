### C14S02Q18
![image](https://github.com/user-attachments/assets/9dcf4fea-64a4-4b0b-bc40-a146ecd8f3d3)

$H_0: p_1 = p_2 = p_3 = \frac{1}{3}, H_a:$ at least a $p_i$ is different from others.

$\alpha=0.05$

The test statistic:

$x^2 = \sum \frac{(O_i-E_i)^2}{E_i} \sim x^2_{k-1}$

Realized test statistic:

$E_i = np_i = \frac{83+61+56}{3} = 66.667$

${x^2}^* = \sum \frac{(O_i-E_i)^2}{E_i} = \frac{(83-66.667)^2}{66.667} + \frac{(61-66.667)^2}{66.667} + \frac{(56-66.667)^2}{66.667} = 6.190$

Reject region:

$x^2_{\alpha,(k-1)}={x^2}_{0.05,2}=5.99147$

Since ${x^2}^*= 6.190 > 5.99147$, we reject $H_0$ and say there is sufficient evidence to indicate that the data in the table indicate that there is a difference in preference for the three entrances.

The 95% C.I. :

$p = \hat{p} \pm Z_{\alpha/2} \sqrt{\frac{\hat{p}(1 - \hat{p})}{n}} = 0.415 \pm 1.96 \sqrt{\frac{0.415(1 - 0.415)}{200}} = (0.347, 0.483)$

### C14S02Q22
![image](https://github.com/user-attachments/assets/0663d8b8-e6c6-47e4-9bcf-21f58742831f)

$H_0: \quad p_1 = p_2 = p_3 = p_4 = p_5 = p_6 = p_7 = \frac{1}{7}, H_a: at least one p_i is different from others.$

$\chi^2_{STAT} = \sum \frac{(O_i - E_i)^2}{E_i} \sim \chi^2_{df = n - 1}$

$E_i = \frac{200}{7} \approx 28.57$

$\chi^2 = \frac{(24 - 28.57)^2 + (36 - 28.57)^2 + (27 - 28.57)^2 + \cdots + (29 - 28.57)^2}{28.57} \approx 3.63$

$\chi^2_{6, 0.05} = 12.5916$

Since ${x^2}^*= 3.63 < 12.5916$, we don't reject $H_0$ and say there is no sufficient evidence to indicate that heart attack incidence differs by day.
