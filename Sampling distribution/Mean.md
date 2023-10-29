---
tags:
  - 🌱
  - Statistics
  - Math
date: 15--Aug--2022
---

# Mean

## Relation to central tendency
Minimises absolute square differences for each $x$ in dataset
Refer to [[Sample mean]] and [[Population mean]]
## Question
### Why [[Variance]] use mean instead of [[Median]]
- The mean minimises the [[Mean squared error]]
- The [[Median]] minimises the [[Median Absolute difference]]
#### Proof
let $\mu = (x_1+...x_n)/n$, then the sum of all squared error equals
$$\sum_{i=1}^n (x_i - \mu)^2 = \sum_{i=1}^n (x_i^2 - \mu^2 + 2\mu x_i)$$
Simplifying the equation, we obtain
$$x_1^2 + ... +x_n^2 - n\mu^2 + 2\mu(x_1 +...+ x_n)$$
To obtain the value of $\mu$ that minimises the equation, apply [[Differentiation]]
$$\begin{align}
&\frac{d}{d\mu}x_1^2 + ... +x_n^2 - n\mu^2 + 2\mu(x_1 +...+ x_n)=0&\\
&-2n\mu + 2(x_1 +...+x_n)=0&\\
&\mu = \frac{x_1 +...+x_n}{n}
\end{align}$$

---
Links: 