---
tags:
  - 🌱
  - Statistics
  - Math
date: 11--Jul--2022
---

# [[Confidence interval]] for mean

Computing mean of the sample to estimate mean of the population.

## Example

95% (1.96 SD from mean) of [[Sampling distribution]] image is shaded.

Implication: For random sample, the sample mean computed lying within this 95% has probability of 0.95. By extension, repeated computation will create an interval range containing the population mean 95% of the time.

![[sampling distribution of the mean.png]]

## Formula (SD known)

> [!important]
> Population SD must be known to apply formula

$$\text{Lower limit} = M - Z_{0.95}\sigma_M$$
$$\text{Upper limit} = M + Z_{0.95}\sigma_M$$

1. M is the sample mean
2. Z the number of SD of [[Normal distribution]] from mean
3. $\sigma$ the standard error of mean

## Formula (SD unknown)

Use of [[t distribution]] to estimate SD from sample data, where t is estimated based on [[Degree of freedom]].

Mean and variance are calculated from sample. We apply the [[Standard error of mean]] formula modified to compute an estimate of the standard error.

$$s_M =\frac{s}{\sqrt{N}}$$



---
Links: 