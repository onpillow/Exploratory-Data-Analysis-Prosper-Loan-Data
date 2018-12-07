# Exploration of Loan Dataset from Prosper
The project is about exploratory data analysis(EDA) of a loan dataset from Prosper in R language, which is a part of Udacity Data Analyst Nanodegree.

[Click here](http://rpubs.com/onpillow/446310) to see the Prosper Loan EDA report.

## Overview
Prosper is a leading financial peer-to-peer lending platform company which connects borrowers and investors. In this Prosper loan data set, it roughly contains four kinds of loan data information — Loan Status, Borrower Data, Loan Information Data and Credit Risk Matrices during 2005 to 2014. I started by understanding some stories about Prosper and exploring the individual variables related to my initial question of interest — **What factors are connected to defaulted/completed loan?** Then I found Prosper have improved their credit measurement system by Prosper Rating from only using Credit Score before. And I continued to make observations on plots through using R language and ggplot2, then I make assumption that maybe Prosper put more weight of Prosper Prosper Score than Credit Score in their Prosper Rating. I kept exploring features related to Prosper Score and relationship between Prosper Score and these features and Loan Status. Eventually, I pick features that I observed that having some trends with Loan Status and Prosper Score. I created a Logistic model to predict the likelihood of a loan would be high risk or completed using these features.

## Data
This Prosper loan data set can be download from [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1544172248160000) which was provided by Udacity. The dataset contains 113,937 loans with 81 variables on each loan, for more variable definition, see the [link](https://www.google.com/url?q=https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit?usp%3Dsharing&sa=D&ust=1544172608919000).

## License
[MIT License](https://github.com/onpillow/Exploratory-Data-Analysis-Prosper-Loan-Data/blob/master/LICENSE)