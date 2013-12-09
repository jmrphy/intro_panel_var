---
title       : Very Quick Introduction to Panel VAR for Political Scientists
subtitle    : Justin Murphy, University of Southampton
author      : jmrphy.net
job         : '@jmrphy'
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : mathjax            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Plan

1. What is VAR?
2. What is Panel VAR?
3. What can one use it for?
4. An example

---

## What is VAR?

> - "Vector autoregression" refers to an "*n*-equation, *n*-variable linear model in which each variable is in turn explained by its own lagged values, plus current and past values of the remaining n - 1 variables." (Stock and Watson 2001)

> - Standard tool of econometrics since the 1980s (Sims 1980).
    - Somewhat controversial because it's rather atheoretical
    
> - At a minimum, VAR is a powerful tool for revealing the "stylized facts" of covariation in time series data

---

## What is Panel VAR?

Pools the time-series of multiple units (Hood et. al 2008; Hurlin and Venet 2001):

$$ y_{i,t} = \alpha_{i} + \sum_{k=1}^p \gamma^{(k)} y_{i,t-k} + \sum_{k=0}^p \beta_i^{(k)} x_{i,t-k} + v_{i,t} $$

for each of the cross-sections *i* and for all *t* in [1,T].




