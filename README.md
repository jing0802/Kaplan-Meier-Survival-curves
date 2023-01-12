# KaplanMeier-Plot

The Kaplan-Meier estimator is used to estimate the survival function, which shows the probability of an event (for example, survival) within a certain time interval. It's usually visualized as survival curves.

Here, I will use the `survfit()` function in `survival` package to estimate survival curves for censored data and use the `ggsurvplot()` function of the `survminer` package to plot survival curves.

1. Install and load R packages
```
install.packages("survival")
install.packages("survminer")
library(survival)
library(survminer)
library(tidyverse)
library(ggplot2)
```

