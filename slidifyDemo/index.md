---
title       : Developing Data Products - Coursera Project Assignment
subtitle    : January 31, 2016
author      : Seon Su Kim
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Project Detail

A simple Shiny application has been built and published to generate the linear regression between two variables of the mtcars dataset.

In this application the user choose the predictor and outcome is always fixed as mpg.

---

## Summary of dataset

About mtcars dataset : The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973~74 models).

The mtcars dataset has 32 entries with 11 columns. The mileage (mpg) variation summary is as follows:


---

## It works like this..

[1] The use select the predictor
[2] The user selesct a color of the regression line
[3] In both the cases, when the user make a choice, the plot is updated
[4] It also shows the summary of the predicted varibale selected

---

## Regression Example

Sample Regression

```r
qplot(wt, mpg, data = mtcars)
```

<img src="assets/fig/simple-plot-1.png" title="plot of chunk simple-plot" alt="plot of chunk simple-plot" style="display: block; margin: auto;" />
