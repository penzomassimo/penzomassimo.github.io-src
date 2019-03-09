Title: What is a QQ-Plot
Date: 2018-12-16 10:20
Category: concepts

#### Intuition
This is what a QQ-plot looks like

![Alt Text](/images/qq_plot.svg)

A QQ-plot is a graphical technique used to determine if two datasets come from populations with a common distribution.

QQ-plots are often used to determine whether a dataset is normally distributed. As the name suggests, the horizontal and vertical axes of a QQ-plot are used to show quantiles.

A QQ-plot is a scatter plot of the quantiles of the first data set against the quantiles of the second data set. By a quantile, we mean the fraction (or percent) of points below the given value. That is, the 0.3 (or 30%) quantile is the point at which 30% percent of the data fall below and 70% fall above that value.

A 45-degree reference line is also plotted. If the two sets come from a population with the same distribution, the points should fall approximately along this reference line. The greater the departure from this reference line, the greater the evidence for the conclusion that the two data sets have come from populations with different distributions.

[For information about quantiles follow this link]({filename}./quantiles.md)

#### Theory



$$
Z = 2
$$

#### How to build a QQ-Plot in R

```
my_data <- ToothGrowth
qqnorm(my_data$len, pch = 1, frame = FALSE)
qqline(my_data$len, col = "steelblue", lwd = 2)
```

And this is what we get:

![Alt Text](/images/qq_plot.svg)



#### How to build a QQ-Plot in R
```

+----+------+-------+
| i  |  yi  |  zi   |
+----+------+-------+
|  1 | 21.7 | -1.64 |
|  2 | 22.4 | -1.04 |
|  3 | 22.8 | -0.67 |
|  4 |   25 | -0.39 |
|  5 |   25 | -0.13 |
|  6 | 25.9 |  0.13 |
|  7 | 25.9 |  0.39 |
|  8 | 26.4 |  0.67 |
|  9 | 27.7 |  1.04 |
| 10 | 28.9 |  1.64 |
+----+------+-------+

```

