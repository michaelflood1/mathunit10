# Unit 10 two parameter hypothesis testing

statistical methods to detect a difference between two populations

### difference of two population proportions

$p_{1} - p_{2}$

### difference of two population means

$\mu _{1} - \mu _{2}$

### $Z_{stat}$ for two proportions

$Z_{stat} = \frac{\left(\hat{p}_1 - \hat{p}_2\right) - \left(p_1 - p_2\right)}{\sqrt{\bar{p}(1 - \bar{p}) \left(\frac{1}{n_1} + \frac{1}{n_2}\right)}}$

$\hat{p}$ = sample proportion

$p$ = population proportion

$\bar{p} = \frac{x_1 + x_2}{n_1 + n_2} = $ combined proportion of success accross both groups

## REQUIREMENTS TO USE THE $Z_{stat} formula

Requirements:
-  The two random samples are from two independent populations.
- For each sample, **both** must be true:
    - $np \geq 5 =  (np_1 \geq 5)  (np_2 \geq 5)$
    - $nq \geq 5 = (1 - \bar{p}_{1} \geq 5), (1- \bar{p}_{2} \geq 5)$


### $T_{stat}$ for two means

$t_{stat} = \frac {(\bar{x}_1 - \bar{x}_2) - (\mu _1 - \mu _2)}{\sqrt \frac {S_{1}^2}{n_{1}} + \frac {S_{2}^2}{n_{2}}}$

$\bar{x}_{1/2}  = \frac {sum of values in sample 1/2}{sample size of group 1/2}$ 

$\sqrt \frac{S_{1/2}^2}{n_{1/2}} =$ sample 1/2 variance


## REQUIREMENTS TO USE THE $t_{stat} formula

- - The two **random** samples are from two **independent** populations

- - For each sample at least one must be true
    - The sample size is large i.e $ n_{1} \geq 30, n_{2} \geq 30$
    - the population is normal
        - $Range = Max - Min$
        - $standard deviation = s = \sqrt \frac{\sum (x_{i} - \bar{x})^2}{n-1}$
        - $Ratio = \frac {Range}{s}$
        - if ratio $\approx $ within 4 to 6
        - likely normal
    - $\hat{x}$ = mean of data
    - $x_{i}$ = each individual data point in set
    - $n$ = number of data points
    - $\sum$ = the sum of following quantites




