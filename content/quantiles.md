Title: What's a Quantile?
Date: 2018-12-16 10:20
Category: concepts

So, what is a quantile?

In general we can say that quantiles are just lines that divide the dataset in equally sized groups.
For example, the 0.5 quantile is a line where 50% of the data is above it and 50% of the data is below it.

Common Quantiles

Certain types of quantiles are used commonly enough to have specific names. Below is a list of these:

- The 2 quantile is called the median
- The 3 quantiles are called terciles
- The 4 quantiles are called quartiles
- The 5 quantiles are called quintiles
- The 6 quantiles are called sextiles
- The 7 quantiles are called septiles
- The 8 quantiles are called octiles
- The 10 quantiles are called deciles
- The 12 quantiles are called duodeciles
- The 20 quantiles are called vigintiles
- The 100 quantiles are called percentiles
- The 1000 quantiles are called permilles

Here is how you calculate quantiles of the `petal_lentgh` variable in a pandas dataframe in Python:

```
df['petal_length'].quantile([0.25, 0.50, 0.75])

0.25    1.60
0.50    4.35
0.75    5.10
Name: petal_length, dtype: float64
```

Here we have just calculated the `0.25`, `0.50` and `0.75` quantiles
