[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

```python
import nsfg
import numpy as np

preg = nsfg.ReadFemPreg()
live = preg[preg.outcome == 1]

firsts = live[live.birthord == 1]
others = live[live.birthord != 1]

firsts_mean = firsts.totalwgt_lb.mean()
others_mean = others.totalwgt_lb.mean()

firsts_n = len(firsts.totalwgt_lb)
others_n = len(others.totalwgt_lb)
firsts_var = firsts.totalwgt_lb.var()
others_var = others.totalwgt_lb.var()

pooled_var = (firsts_n * firsts_var + others_n * others_var) / (firsts_n + others_n)
cohens_d = (firsts_mean - others_mean) / pooled_var

print("First Babies Mean:", firsts_mean)
print("Other Babies Mean:", others_mean)
print("Cohen's D:", cohens_d)
```
