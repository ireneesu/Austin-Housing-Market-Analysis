# Austin Housing Market Analysis

## Table of Contents

- [Project Overview](#project-overview)    
- [Data Description](#data-description)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling Selection](#modeling-selection)
- [Result/Findings](#resultfindings)
- [Limitations](#limitations)
- [References](#references)



### Project Overview 
 The project mainly focuses on the analysis of house prices in the Austin area. I worked with Qingci Luo, Yisheng Chen and Chang Wang to solve the problems as a group. We are trying to find what are the main features that influence the real estate sale price in Austin, as the Austin Housing market was one of the hottest markets in 2021, and these listings show how that market has changed over the past couple of years. The project includes the entire process of analyzing the data, cleaning the data, picking relevant features, modeling, and evaluation.

### Data Description   
- [Download here](https://www.kaggle.com/datasets/ericpierce/austinhousingprices)

Our dataset, Austin, TX House Listings, was downloaded from Kaggle. The original uncleaned dataset consisted of over 700 columns and Eric made this clean set of features and uploaded
them on the website as sources. The dataset contains 15,171 listings with 45 features, one key column, and one image name which references an image in the home Images folder.

### Tools

- Python
    - Data Cleaning
    - Data Analysis
    - Data Visulization

### Data Preparation 

In the initial data preparation phase, we performed the following task:

1. drop all the duplicate and missing value to ensure data integrity.
2. convert the data type of several boolean columns to integer.
3. perform the one-hot encoding for the categorical variable.
4. remove outliers by using the Mahalanobis distance.
5. feature selection by reducing the number of irrelevant or redundant features.
  
### Exploratory Data Analysis 

EDA involoved exploring the hr data to answer key questions, such as:

1. Which variables have the strongest relationship with the response variable Price?
2. Which model has better performance in predicting the response variable Price?

### Modeling Selection

In the modeling establishing and selection phase, we focused on and the improvement of performance:

1. Linear regression model
2. Least Absolute Shrinkage and Selection Operator (LASSO)
3. Principal Component Regression (PCR)
4. Tree-Based Model & Ensemble Learning
   

### Result/Findings
By combining various machine learning techniques and feature selection methods, we were able to create a robust model that can effectively predict house prices in the Austin area. This model can be a valuable tool for real estate investors, homebuyers, and policymakers to
make informed decisions in the housing market since the comprehensive and rigorous data preprocessing to ensure that the model is making predictions or classifications based on relevant
and accurate information.


### Limitations
One potential limitation would be that the model was trained and tested on a specific dataset from a particular region, and its performance may be influenced by the unique characteristics and patterns of that region.

### References
1. Leung, K. (2022, September 14). Principal component regression - clearly explained and implemented. Medium. Retrieved May 3, 2023, from https://towardsdatascience.com/principal-component-regression-clearly-explained-and-implemented-608471530a2f

2. Pierce, E. (2021, April 12). Austin, TX House listings. Kaggle. Retrieved May 3, 2023,from https://www.kaggle.com/datasets/ericpierce/austinhousingprices

3. Géron, A. (2020). Hands-on machine learning with scikit-learn, Keras, and tensorflow: Concepts, tools, and techniques to build Intelligent Systems. O'Reilly.
