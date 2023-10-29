---
tags:
  - 🌱
  - Statistics
  - Math
date: 05--Aug--2022
---

# Percentile

>[!Note]
>Data must be arranged in order before calculation

## Definitions of percentile

3 types of definition of rank

1. Value must be greater than
2. Value must be greater or equal to
3. ==Allows interpolation==

## Formula

Handling case where rank is not an integer

$$R=percentile/100 \times (N+1)$$

Obtain the fractional part of rank and apply interpolation to obtain percentile value

$$(FR)(Value_{rank+1}-Value_{rank})+Value_{rank}$$

## Applications

Given a case where a student's score is in the 70th percentile, then we can say that his score is higher than 70% of the population.