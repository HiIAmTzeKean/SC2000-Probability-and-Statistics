---
tags:
  - 🌱
  - Statistics
  - Math
date: 20--Aug--2022
---

# Bayes Theorem

Considers prior probability to determine posterior probability. Thus, when given $P(A|B)$ we can find $P(B|A)$.

## Rule 1
Given 2 events A and B, where $P(A) \ne 0$

$$P(B|A)  = \frac{P(A|B)P(B)} {P(A)}$$

## Rule 2
If there is some partition in the sample space where $B_1, B_2...$ and A is some event where $P(A) \ne 0$ then

$$P(B_j|A) = \frac{P(A|B_j)P(B_j)} {\sum P(A|B_i)P(B_i)}$$
so for some sample space with 2 partition, we can rewrite the equation to
$$P(B|A)=\frac{P(A|B)P(B)}{P(A|B)P(B) + P(A|B')P(B')}$$

Refer to YouTube <https://www.youtube.com/watch?v=HZGCoVF3YvM>
Refer to website for more <https://www.probabilitycourse.com/chapter1/1_4_3_bayes_rule.php>

---
Links: 