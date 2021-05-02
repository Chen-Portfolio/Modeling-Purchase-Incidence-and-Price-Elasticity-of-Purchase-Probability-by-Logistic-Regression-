# Modeling Purchase Incidence and Price Elasticity of Purchase Probability
## Table of Content
  - [Project Overview](#projectoverview)
  - [Data Description](#datadescription)
  - [Technical Overview](#technicaloverview)
  - [Results](#results)

***

<a id='projectoverview'></a>
## Project Overview

In this project, customers' purchase behavioral and demographical data of an online E-commerce chocolate shop have been analyzed in order to predict purchase incidence for each customer visiting the store. Besides, a price elasticity analysis built on purchase probability for each customer segment has also been performed in order to examine the responses to price changes for each customer group. This project would support the marketing department of a company to see the turning point for the product price from ineslatice to eslatict then further decide increase or decrease price.


This project is divided into five steps:

1. `Data Preparation` in this part, feature scaling was to standardize the dataset and a segmentation model (saved before) was applied to segment the dataset into four customer segments and each row of the dataset was labelled.

2. `Modeling Purchase Model` in this part, by choosing "Incidence" as dependent variable, calculated mean price as independent variable and running Logistic Regression model, 
the stanardized dataset was trained and a negative model coefficient was shown quantifying the exact relationship between price and purchase probability.

3. `Price Elasticity of Purchase Probability` in this part, by choosing a price range, the purchase probability for purchasing or not at each price point was examined, and moreover, by applying price elasticity formular (Formula: E = beta * Price * ( 1 - Pr(purchase))) each price and its corresponding price elasticity was visulaized, which is able to determine the average customers' purchase behavior.

4. `Price Elasticity of Purchase Probablity by Each Segment` in this part, the price elasticity of purchase probability was run for each customer segment so that the four easticity lines for each segment were compared directly to see which group is more sensitive to price and at what range of the price. 

<a id='datadescription'></a>
## Data Description

The dataset contains 500 customers transaction data on a daily basis for two years in an online store selling chocolate as well as their demographical data. For each day, the dataset shows whether the individual visited the store, purchased or not, purchased quantity, purchased price, with promotion or not, and the corresponding brand, etc. And, the dataset has been preprocessed by encoding the variables in order to transforming certain variables into categorical type.

<a id='technicaloverview'></a>
## Technical Overview

The project has been divided into various steps which include:
* Data Exploration and Manipulation
* Feature Scaling
* Applying segmentation model
* Logistic Regression Model
* Price Elasticity Formular
* Visualization by matplotlib and seaborn


<a id='results'></a>
## Results

The results have been clearly documented in the Jupyter Notebook. Please refer [Customer Segmentation Project Workbook.ipynb](Customer_Segmentation_Project_Workbook.ipynb) as well as the visualization result of the four customer segmentation showed as below:

![](/images/Price_Elasticity_of_Purchase_Probability.png)
