# Medical Insurance Charge Prediction

A regression project that predicts individual medical insurance charges from personal and health attributes — directly relevant to actuarial pricing and risk assessment work.

## The problem

Healthcare costs are one of the most significant financial pressures on individuals, insurers, and society. Using a dataset capturing age, sex, BMI, number of children, smoking status, and region alongside actual billed insurance charges, this project builds a predictive model for expected charges. The goal is two-fold: understand which factors most strongly drive medical costs, and provide a reliable cost-estimation tool that could support risk-based pricing decisions.

## What this covers

- Data cleaning and exploratory data analysis of the insurance dataset
- Investigating how age, BMI, smoking status, number of children, and region each relate to charges
- Building and evaluating regression models to estimate expected charges from these features
- Interpreting which factors carry the most weight — smoking status and BMI are classic strong predictors in this kind of dataset

## Why this one matters most to me

As an Actuarial Science student, this is the closest of my ML projects to real actuarial work: turning individual risk factors into a defensible cost estimate is the same fundamental problem actuaries solve when pricing health and life insurance products.

## Stack

Python · pandas · numpy · seaborn/matplotlib · scikit-learn (regression models)

## File

`insurance_final.ipynb`
