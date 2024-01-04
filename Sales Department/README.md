# SalesProphet: Forecasting Future Daily Sales with Facebook Prophet

## Project Overview

Companies aiming for competitiveness and accelerated growth can leverage AI/ML to develop predictive models for forecasting sales. This project involves working as a data scientist in the sales department, where the goal is to predict future daily sales based on historical data from 1115 stores. The provided dataset includes various features such as store ID, daily sales, number of customers, store status (open/closed), promotional activities, holidays, store type, assortment, competition information, and more.

## Objective

The main objective of this project is to use Facebook Prophet, an open-source forecasting tool, to build predictive models that can accurately forecast future daily sales. The models should consider historical data, seasonality effects, demand, holidays, promotions, and competition.

## Key Skills

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Preprocessing
- Data Visualization
- Time Series Forecasting
- Facebook Prophet

## Input Data

The dataset consists of the following features:

- **Id:** Transaction ID (combination of Store and date)
- **Store:** Unique store ID
- **Sales:** Sales per day (target variable)
- **Customers:** Number of customers on a given day
- **Open:** Boolean indicating whether a store is open or closed (0 = closed, 1 = open)
- **Promo:** Describes if the store is running a promo on that day or not
- **StateHoliday:** Indicates which state holiday (a = public holiday, b = Easter holiday, c = Christmas, 0 = None)
- **SchoolHoliday:** Indicates if the (Store, Date) was affected by the closure of public schools
- **StoreType:** Categorical variable indicating the type of store (a, b, c, d)
- **Assortment:** A = basic, b = extra, c = extended
- **CompetitionDistance:** Distance to the closest competitor store
- **CompetitionOpenSince [Month/Year]:** Date when competition was open
- **Promo2:** Indicates whether the store is participating in Promo2 (0 = store is not participating, 1 = store is participating)
- **Promo2Since [Year/Week]:** Date when the store started participating in Promo2
- **PromoInterval:** Describes the consecutive intervals Promo2 is started, naming the months promotion is started anew.

## Facebook Prophet

Prophet is open source software released by Facebook’s Core Data Science team. It is designed for forecasting time series data, incorporating additive models with non-linear trends, yearly, weekly, and daily seasonality, and holiday effects. Prophet is particularly effective for time series with strong seasonal effects and multiple seasons of historical data.
