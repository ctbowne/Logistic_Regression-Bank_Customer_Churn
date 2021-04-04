# Software and versions
R version 4.0.3 (2020-10-10)

RStudio
Version 1.2.5033
© 2009-2019 RStudio, Inc.
"Orange Blossom" (330255dd, 2019-12-04)
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.1 Chrome/69.0.3497.128 Safari/537.36

# Packages and versions
* car v3.0-10, 
* caret v6.0-86, 
* fastDummies v1.6.3, 
* PerformanceAnalytics v2.0.4, 
* rcompanion v2.3.26, 
* readr v1.4.0, 
* ROCR v1.0-11, 
* tidyverse v1.3.0, 
* sjPlot v2.8.6, 
* visreg v2.7.0

# Project 1 Overview: Predicting Customer Churn?
* This was an educational project

* It is cheaper to retain customers than aquire them. Just like any business, banks wish to limit customer exits (the churn) by predicting who is at risk. 
* Goal: Answer the question: can we predict who is likely to leave the bank using logistic regression?
* Data: 10,000 customer accounts defined by 11 variables. Split into training and testing.  Outcome variable is binary: true if customer leaves bank.
* Analysis: Frequencies in catagorical variables checked. Some variables transformed and variable correlations checked.
* Model: Outcome variable of interest is binary. Backwards elimination is used. Interactions explored. Influence/leverage points checked. Model significance checked.
* Prediction outcomes: Model correctly predicts a customer will leave 34% of the time. The overall accuracy is 84%. Model fails due to Type II error.

# Project 1 collaborators:

* Airi Oye
* Brayden Nicholl
* Chris Bowne
* Gurami Kavrelishvili
* Krishna Dave
* Sasha Farizn-Nia
* Shu Lee
