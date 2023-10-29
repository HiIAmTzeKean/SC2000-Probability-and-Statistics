---
tags:
  - 🌱
  - Statistics
  - Math
date: 05--Aug--2022
---

# Box plots

## Properties

- Useful for comparing distribution
- Useful for identifying outliers

## Architecture

|       Name        |                Formula                 |
|:-----------------:|:--------------------------------------:|
|    Upper hinge    |            75th percentile             |
|    Lower hinge    |            75th percentile             |
|     H-spread      |    Upper hinge - lower hinge (IQR)     |
|       Step        |             1.5 x H-spread             |
| Upper inner fence |           Upper hinge + Step           |
| Lower inner fence |           Lower hinge - Step           |
| Upper outer fence |          Upper hinge + 2Step           |
| Lower outer fence |          Lower hinge - 2Step           |
|  Upper adjacent   | Largest value below Upper inner fence  |
|  Lower adjacent   | Smallest value above Lower inner fence |
|   Outside value   |    Beyond Inner fence but not outer    |
|   Far out value   |           Beyond outer fence           |
|                   |                                        |

Note: **Whiskers** are drawn from hinge to adjacent value

[[Outlier]] are then defined as values outside of the inner fences. Thus, outside value and far out value can be defined as outliers.

---
Links: [[Percentile]]