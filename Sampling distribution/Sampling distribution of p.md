# Sampling distribution of p

Random sample of n observations selected from [[Binomial distribution]] with [[Parameter]] p, and we want to find $\bar{p}$ sample statistics.

## Formula

### Mean
We have to divide the mean of the [[Binomial distribution]] by N to adjust for obtaining the mean of successes. Thus, the mean of sampling distribution of p is the probability of success.
$$\mu_p = \frac{x}{n} = \frac{n \pi}{n} = \pi, \text{where x is the number of successes and n is the sample size}$$

### Standard deviation
Since we are applying [linear transformation](Linear%20transformation.md) on the data points by dividing by N, the standard deviation will also be transformed by N. Recall [binomial distribution variance](Binomial%20distribution.md#Variance).
$$\sigma = \frac {\sqrt{n\pi(1-\pi)}}{n}= \sqrt{\frac{\pi(1-\pi)}{n}}$$


