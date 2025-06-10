# NBA Load Management & Performance Analysis

This repository contains the code and data analysis for a research project exploring the relationship between load management (i.e., rest days), team performance, and player injury patterns in the NBA. The project integrates game-level statistics, injury history, and machine learning models to evaluate how rest affects performance and predict game outcomes.

## Content:
* TeamData.rmd: Exploratory data analysis for team performance/winning vs. rest days
* PlayerInjury.rmd: Exploratory data analysis for player injury
* XGBoostModel.ipnyb: XGBoost model for predicting wins/losses using rest days

## Datasets Used
All datasets are publicly available on Kaggle:

* [NBA Games – Nathan Lauga](https://www.kaggle.com/datasets/nathanlauga/nba-games) 

* [NBA 10-Year Injury History – Mustafa Büyüknacar](https://www.kaggle.com/datasets/buyuknacar/active-nba-players-10-year-injury-history) 

* [NBA Player Stats 2016–2017 – Abdurahman Maarouf](https://www.kaggle.com/datasets/abdurahmanmaarouf/nba-players-stats-2016-2017) 

## Project Goals
* Analyze how rest days affect team performance across key offensive statistics

* Identify any patterns between player age/minutes and injury risk

* Build an XGBoost model to predict win/loss outcomes using rest days and performance stats

* Assess the reliability of rest as a predictor of success or injury
