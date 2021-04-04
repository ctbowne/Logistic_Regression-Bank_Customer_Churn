# Computer:
* Edition: Windows 10 Home
* Version: 20H2
* OS Build: 19042.867

# Software and versions
R version 4.0.3 (2020-10-10)
RStudio Version 1.2.5033
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

# Overview: Predicting Customer Churn?
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

![](01_title.png)
![](02_abstract.png)
![](03_dataset.png)
![](04_outcome_var.png)
![](05_pred_vars.png)
![](06_selection_method.png)
![](07_cat_graphs.png)
![](08_Has_Credit.png)
![](09_Gender.png)
![](10_Geography.png)
![](11_Active_Mem.png)
![](12_corr.png)
![](13_cat_Balance.png)
![](14_cat_Credit.png)
![](15_cat_NoProducts.png)
![](16_transf.png)
![](17_credit_sc.png)
![](18_age.png)
![](19_tenure.png)
![](20_balance.png)
![](21_salary.png)
![](22_final_mod.png)
![](23_model_graph.png)
![](24_coeff.png)
![](25_log_odds.png)
![](26_interpr.png)
![](27_odds_graph.png)
![](28_other_plots.png)
![](29_hypoth.png)
![](30_outliers.png)
![](31_interact.png)
![](32_interact1.png)
![](33_interact2.png)
![](34_interact3.png)
![](35_interact_interp.png)
![](36_contig.png)
![](37_ROC.png)
![](38_sum_concl.png)
![](39_rec.png)