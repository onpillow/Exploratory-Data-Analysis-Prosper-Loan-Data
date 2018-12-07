# Exploration of Loan Dataset from Prosper

Exploratory data analysis(EDA) of a loan dataset from Prosper in R language.

[Click here](http://rpubs.com/onpillow/446310) to see the Prosper Loan EDA report.

## Overview
This Prosper loan data set roughly contains four kinds of loan data information — Loan Status, Borrower Data, Loan Information Data and Credit Risk Matrices during 2005 to 2014. I started by understanding some stories about Prosper and exploring the individual variables related to my initial question of interest — **What factors are connected to defaulted/completed loan?** Then I found Prosper have improved their credit measurement system by Prosper Rating from only using Credit Score before. And I continued to make observations on plots through using R language and ggplot2, then I make assumption that maybe Prosper put more weight of Prosper Prosper Score than Credit Score in their Prosper Rating. I kept exploring features related to Prosper Score and relationship between Prosper Score and these features and Loan Status. Eventually, I pick features that I observed that having some trends with Loan Status and Prosper Score. I created a Logistic model to predict the likelihood of a loan would be high risk or completed using these features.

## License
[MIT License](https://github.com/onpillow/Exploratory-Data-Analysis-Prosper-Loan-Data/blob/master/LICENSE)
