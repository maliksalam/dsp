[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

```
import numpy as np
import thinkstats2
import thinkplot

d = np.random.random(1000)

pmf = thinkstats2.Pmf(d, label='pmf')
thinkplot.Pmf(pmf, linewidth = 0.1)
thinkplot.Config(xlabel='Random variable', ylabel='Probability')
thinkplot.Show()

cdf = thinkstats2.Cdf(d, label='cdf')
thinkplot.Cdf(cdf)
thinkplot.Config(xlabel='Random variable', ylabel='Cumulative')
thinkplot.Show()
```
