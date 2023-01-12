# KaplanMeier-Plot

The Kaplan-Meier estimator is used to estimate the survival function, which shows the probability of an event (for example, survival) within a certain time interval. It's usually visualized as survival curves.

Here, I will use the `survfit()` function in `survival` package to estimate survival curves for censored data and use the `ggsurvplot()` function of the `survminer` package to plot survival curves.

1. Install and load R packages
<img width="390" alt="Screen Shot 2023-01-11 at 10 12 28 PM" src="https://user-images.githubusercontent.com/52009184/211974172-b06bdc32-d4ef-4561-95f2-ea8dd8017deb.png">

install.packages(survival)
install.packages(survminer)
library(survival)
library(survminer)
library(tidyverse)
library(ggplot2)
```

