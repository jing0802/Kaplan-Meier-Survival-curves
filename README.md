# KaplanMeier-Plot

The Kaplan-Meier estimator is used to estimate the survival function, which shows the probability of an event (for example, survival) within a certain time interval. It's usually visualized as survival curves.

Here, I will use the `survfit()` function in `survival` package to estimate survival curves for censored data and use the `ggsurvplot()` function of the `survminer` package to plot survival curves.

## Install and Load R packages

 <img width="322" alt="Screen Shot 2023-01-11 at 11 50 44 PM" src="https://user-images.githubusercontent.com/100873921/211988029-7477f069-6b16-4fae-a386-30b399799ca2.png">

## Load Data
Here, I will use the **lung** dataset of the `survival` package to demonstrate.



