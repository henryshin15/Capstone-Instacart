# Market Basket Analysis - Instacart Data
# Capstone Project
## Business Problem
Groceries2Go, a made up grocery store with online purchasing ability wants to predict which previously bought products a customer has purchased will be in its next order (primary goal) and wants to implement a recommendation system that suggests products based on the customer's basket, shopping history, and from other people's similiar baskets and their products (secondary goal). 

## Data Science Major Concepts
  * Market Basket Analysis (Primary Goal)
  * Cluster Analysis (Secondary Goal)
  * Natural Language Processing (Secondary Goal)
  * Reccomendation Systems: Collaborative Filtering & Content-Based (Secondary Goal)

## About Dataset
The data is from a [Kaggle](https://www.kaggle.com/competitions/instacart-market-basket-analysis/code) competition about Instacart's customer's orders over time. The dataset is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. 

The data is divided into 6 files:  
<br/>

**Products.csv**: 49,688 Unique product ids, with description, aisle id, and department id\
**Aisles.csv**: 134 Unique aisle numbers and descriptions  
**Departments.csv**: 21 Unique department numbers and descriptions  
**Order_products__prior.csv**: Order id, product id, add to cart order, and reorder indicator  
**Order_products__train.csv**: Order id, product id, add to cart order, and reorder indicator\
**Orders.csv**: 3,421,083 Unique order id, with user id, order number, order_dow, order_hour_of_day, days_since_prior_order, and eval_set indicating if the order is in train, prior, or test 

## Methods
1. Feature Engineering Product and Customer to describe customer behavior
2. Feature Importance using Extra Trees Classifier
3. Logistic Regression - Binary classification model for predicting whether or not a customer will reorder a product.

## Modeling


Final Model can predict 75% precisely if a customer reorders a product. 

## Featured Notebooks and Presentation
* [Final Notebook](https://github.com/henryshin15/Capstone-Instacart/blob/main/Final%20Notebook.ipynb)
* [Presentation](https://github.com/henryshin15/Capstone-Instacart/blob/main/Presentation.pdf)



