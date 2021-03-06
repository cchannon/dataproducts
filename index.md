---
title       : App-Based Predictions of vehicle MPG
subtitle    : A new way of accelerating decisions
author      : Charles Channon
job         : Consultant
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Opportunity

As a company, we have a great new opportunity to leverage model-based predicting when making decisions.

--- .class #id 

## Advantages

An R-driven Shiny app will enable us to:

* leverage sophisticated models

* distribute decision-making authority

* develop more fuel efficient vehicles

--- .class #id 

## Solution

Because we're interested in predicting MPG, let's look at the starting model we have already deployed using shiny:


```r
data(mtcars)
model <- lm(mpg~wt*am, mtcars)
model
```

```
## 
## Call:
## lm(formula = mpg ~ wt * am, data = mtcars)
## 
## Coefficients:
## (Intercept)           wt           am        wt:am  
##      31.416       -3.786       14.878       -5.298
```

We'll use this model to predict automatically for users, only requiring them to provide two data points!

--- .class #id

## Benefits

Providing this app interface will allow users to quickly get the answers they need--wihout having to go directly to our data scientists.

This will save everyone time and effort!

--- .class #id

## Thank you

Any questions?


