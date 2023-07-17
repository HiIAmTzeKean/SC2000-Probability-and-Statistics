---
tags: 🌱
date: 05--Aug--2022
---

# Population variance

For a population size $N$,

$\sigma^2 = E[(X - \mu)^2] = \frac{\sum (X-\mu)^2}{N} = \frac{\sum{X^2} - \frac{(\sum X)^2}{N}}{N}$


Note that in the last expression, variance can be simplified further using expected value of [[Population mean]].
$$\frac {\sum X^2 - \frac {(\sum X)^2}{N}} {N} = \frac {\sum X^2}{N} - \frac {\frac{(\sum X)^2}{N}}{N} = E[X^2] - \mu^2$$
This expression is unique to only population variance and does not apply to [[Sample variance]].

---
Links: 