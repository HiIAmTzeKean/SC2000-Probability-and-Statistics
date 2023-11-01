---
tags:
  - 🌱
  - Statistics
  - Math
date: 09--Aug--2022
modified: 30--Oct--2023
---

# Linear transformation
## [[Statistic]]
Given a variable $X$ such that we are going to transform it to $Y=bX+a$
### Effects to mean/ median
The [[Mean]] and [[Median]] are transformed by based on the relationship.
$$mean_Y=b\mu + a$$
### Effects to [[Variance|VAR]]/ [[Standard deviation|SD]]
The addition or subtraction to each data point does not affect the difference to mean -> we only consider the scaling factor.
$$SD_Y=b\sigma$$
$$Var_y=b^2\sigma^2$$
### Effects to [[Covariance]]
Covariance is not affected by linear transformation dealing with addition to each datapoint. It is only affected when the datapoint is multiplied by some constant.

![[covariance and linear transformation.png]]

### Effects to [[Correlation]]/ [[Pearson correlation]]
No effect on correlation. Suppose a relationship of Y and *X* and we now have to find the relationship of *Y* and *(mX+c)* where *m* and *c* are constants. Both correlations are the same.

Refer to image above, since covariance is scaled by some multiple during linear transformation, and standard deviation is also affected by the same multiple. The numerator and denominator cancels out each other.

### Examples
- [[Normalisation]]
- [[Standardisation]]
- [[Centering]]
### Non-linear transformation
- Square root
- Power
- Log
## Relation to [[Linear algebra]]



---
Links: [[Standard deviation]] - [[Variance]]