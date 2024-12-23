# Unit 10 Two-Parameter Hypothesis Testing

Statistical methods to detect a difference between two populations

### Difference of Two Population Proportions

$$p_{1} - p_{2}$$

### Difference of Two Population Means

$$\mu_{1} - \mu_{2}$$

## $Z_{\text{stat}}$ for Two Proportions

$$Z_{\text{stat}} = \frac{\left(\hat{p}_1 - \hat{p}_2\right) - \left(p_1 - p_2\right)}{\sqrt{\bar{p}(1 - \bar{p}) \left(\frac{1}{n_1} + \frac{1}{n_2}\right)}}$$

$\hat{p}$ = Sample proportion

$p$ = Population proportion

$$\bar{p} = \frac{x_1 + x_2}{n_1 + n_2}$$ = Combined proportion of success across both groups

#### REQUIREMENTS TO USE THE $Z_{\text{stat}}$ Formula

Requirements:
- The two random samples are from two independent populations.
- For each sample, **both** must be true:
    - $np \geq 5 \quad \text{or} \quad (np_1 \geq 5) \quad (np_2 \geq 5)$
    - $nq \geq 5 \quad \text{or} \quad (1 - \bar{p}_1 \geq 5), \quad (1 - \bar{p}_2 \geq 5)$


## $T_{\text{stat}}$ for Two Means

$$t_{\text{stat}} = \frac {(\bar{x}_1 - \bar{x}_2) - (\mu_1 - \mu_2)}{\sqrt{\frac{S_1^2}{n_1} + \frac{S_2^2}{n_2}}}$$

$$\bar{x}_{1/2}  = \frac {\text{sum of values in sample 1/2}}{\text{sample size of group 1/2}}$$

$$\sqrt{\frac{S_1^2}{n_1}}$$ = Sample 1 variance


#### $T_{\text{stat}}$ supporting Formula

$$ \text{df} = \min(n_1 - 1, n_2 - 1) \quad t_{\text{crit}} $$

#### REQUIREMENTS TO USE THE $t_{\text{stat}}$ Formula

- The two **random** samples are from two **independent** populations.

- For each sample at least one must be true:
    - The sample size is large i.e. $n_1 \geq 30, \quad n_2 \geq 30$
    - The population is normal:
        - $\text{Range} = \text{Max} - \text{Min}$
        - $\text{Standard deviation} = s = \sqrt{\frac{\sum (x_{i} - \bar{x})^2}{n - 1}}$
        - $\text{Ratio} = \frac{\text{Range}}{s}$
        - If ratio $\approx$ 4 to 6, likely normal.
    - $\hat{x}$ = Mean of data
    - $x_i$ = Each individual data point in set
    - $n$ = Number of data points
    - $\sum$ = The sum of following quantities


####  determine null or alternative hypothesis

---
##### if any claim statement involves a form of equality that claim is the null hypothesis $\eq \geq \leq$

the average students age **is** 22 mentions EQUAL

---

##### if the claim does not involve equality than the claim becomes the alternative hypothesis $\neq \lt \gt$

**less than** 30% of canadians approve of stronger gun laws mentions LESS THAN ( inequal )

---


#### conclusion decision/wording

**for null hypotheses claims**

|Decision|reject null|fail to reject null|
|--|--|--|
|Wording|"there is sufficient evidence to reject the claim that.."|"There is insufficient evidence to reject the claim that..."|

---

**for alternative hypotheses claims**

|Decision|reject null|fail to reject null|
|--|--|--|
|Wording|"there is insufficient evidence to reject the claim that.."|"There is sufficient evidence to reject the claim that..."