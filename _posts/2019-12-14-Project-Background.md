---
title: "Project Background"
date: 2019-12-14
published: true
tags:
  - House Price
  - Data Analysis
excerpt: "The Introduction of our Project"
toc: true
toc_sticky: true
---

## Project Motivation
The housing market in Philadelphia is growing rapidly. Analyzing price trends in the housing market is important for governments, residents and developers. 
- For governments, understanding the trends in house prices can improve decision process. Housing prices can trigger a potential crisis in society. High housing prices tend to accelerate the spatial isolation of the urban area. For example, the rich district and the slum. For that, the ability to predict house prices can help governments to solve social conflicts.
- For residents, the housing price influnces the willing of buying houses. The people buying houses for themselves will considering the area with slow increasing housing price. For the people buying the houses for rent or investment, they desire to buy the houses with high increasing trend. The ability to understand house price trends and predict house prices can provide residents with information on transactions in the housing market.
- For the developers, House prices often have agglomeration effects in a region, and the overall house prices in the region will affect the pricing of self-developed real estate. Understanding the areas where housing prices are growing rapidly can help developers get more returns.

Our project can help people find the housing price increasing trend to help them to make decision.

## Project Expected Deliverbale

 We divide our project into 3 parts:
 
 **1. Data Collection and Data Preprocessing**
 
 Use the OpenDataPhilly data to calculate and visulize the median sale price for each census tract in Philadelphia from 2013 to 2018.
 
 **2. Data Analysis and Visualization**
 
 Calculate and Visualize the yearly median house price from 2013 to 2018 by neighborhoods. 
 
 **3. Predicting the House Price Increase Rate**
- Analyze the trends across census tracts and incorporate other data sets, e.g., Census data or data from open data philly such as new construction permits, Graffiti Call, City Hall.
- Build out a regression model with the data from the previous part, predicting the sales price between the 2018 and 2013 values by census tract and then calculate the predicted price increase rate.

## Project Method
- **Data Collection**: API collecting
- **Data Preprocessing**: Pandas/Numpy, Geospatial Joins
- **Data Visulization**: Altair/Hvplot/Seaborn
- **Prediction** : Scikit-Learn
