[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

```python
import scipy.stats

mu = 178
sigma = 7.7
dist = scipy.stats.norm(loc=mu, scale=sigma)
prob =  dist.cdf(185.4) - dist.cdf(177.8)

print(f"The probability of a male satisfying the requirements is {100 * prob}%")
```
