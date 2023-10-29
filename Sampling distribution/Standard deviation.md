---
tags:
  - 🌱
  - Statistics
  - Math
alias: SD, Standard error
date: 05--Aug--2022
---

# Standard deviation
It is harder to interpret at scale using [[Variance]] compared to standard deviation.
## Standard error derivation
Using
- $\newcommand{\Var}{\operatorname{Var}}\newcommand{\Cov}{\operatorname{Cov}}\Var(X+Y) = \Var(X) + \Var(Y) + 2\cdot\Cov(X,Y)$
- For a constant a, $Var(aX)=a^2Var(X)$
- Reference to [[Variance sum law]]

Since we are assuming that the individual observations are independent the Cov(X,Y) term is 0 and since we assume that the observations are identically distributed all the variances are $\sigma^2$.
$$Var( \frac{1}{n} \sum X_i ) = \frac{1}{n^2} \sum Var(X_i) = \frac{1}{n^2} \times \sum_{i=1}^n \sigma^2= \frac{n}{n^2} \sigma^2 = \frac{\sigma^2}{n}$$


ref: [website](https://stats.stackexchange.com/questions/60484/why-is-the-formula-for-standard-error-the-way-it-is)

---
Links: [[Variance]] - [[Covariance]]