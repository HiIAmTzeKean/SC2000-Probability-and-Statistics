---
tags:
  - 🌱
  - Statistics
  - Math
alias: VAR
date: 05--Aug--2022
---

# Variance
## Procedure variance
When using [[Statistical learning]] methods, each method would introduce some variance
## Variance in [[Machine learning]]
Variance in machine learning defined as
$$Var(X) = \sum (f(x)-\hat f(x))^2$$
where f is the true function and $\hat f(x)$ is the estimate from the machine model.

The goal is to select [[Statistical learning]] method that results in low variance and low [[Bias]]. More [[Flexible model]] tends to result in higher variance indicating [[Overfitting]].

### Consequence of high variance
High model variance indicates
1. More [[Flexible model]]
    1. Slight change in [[Training data]] can lead to drastic changes in prediction
2. Possible [[Overfitting]]
3. Poor [[Generalisation]]
##  Variance of [[Random variable]]
Refer to [@RandomVariabilityPdf](zotero://select/items/@RandomVariabilityPdf) for derivation.

---
Links: 