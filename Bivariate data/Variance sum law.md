---
tags:
  - Statistics
  - Math
---
# Variance sum law

## Variance sum law 1

Considers the linear combination of 2 **independent variables**.

### Example 1
For some linear combination of $X$ and $Y$, where  $T = 5X + 10Y+5$
$$mean = 5 \mu_x + 10 \mu_y +5$$
$$\sigma^2_{x \pm y}=5^2\sigma^2_{x}+10^2\sigma^2_{y}$$

### Example 2
For some linear combination of $X$ and $Y$, where  $T = 5X - 10Y+5$
$$mean = 5 \mu_x - 10 \mu_y$$
$$\sigma^2_{x \pm y}=5^2\sigma^2_{x}+10^2\sigma^2_{y}$$

Take note of how the 2 variables are subtracted in mean, but not in variance. In computation, we always add the variance.

## Variance sum law 2
Deals with dependent variables.

For a population,
$$\sigma^2_{x \pm y}=\sigma^2_{x}+\sigma^2_{y} \pm 2\rho \sigma_x \sigma_y$$
### Example
$$\begin{gather}
&Var(\alpha X + (1-\alpha)Y)\\
&=\alpha^2 Var(X) + (1-\alpha)^2 Var(Y) + 2\alpha(1-\alpha) Cov(X,Y)\\
\end{gather}$$

---
Links: [[Variance]] - [[Linear transformation]] - [[Correlation]]