# California Housing Price (1990)

## Introduction:
A linear regression analysis is performed on california houshing price(1990).
Data were collected from [kaggle](https://www.kaggle.com/harrywang/housing?select=housing.csv).
The motivation of this analysis is:
1. to study the impact of various Normalization technique.
2. First order Ablation study
3. Can we use weights of particular feature as a parameter for
importance of that feature.
4. Feature selection techniques

## Data Summary:

Raw Dataset consist of total 10 columns and 20640 examples. 

Target feature = __median_house_value__

Input features = **['longitude', 'latitude', 'housing_median_age', 'total_rooms',
       'total_bedrooms', 'population', 'households', 'median_income',
       'median_house_value', 'ocean_proximity']**


## Appraoch:
### 1. Pre-processing
  1.1 : Remove outliers
  
  1.2 : Variance Inflation Factor (VIF) analysis
  
  1.3 : Pairwise Correlation analysis using Heatmap

### 2. Experiments
  2.1 : Without Normalization
    
  2.2 : Standardization of input features
  
  2.3 : Max-Min Normalization of input features
  
  2.4 : log transformation of target feature + without Normalization
  
  2.5 : log transformation of target feature + with Standardization

  2.6 : First Order Ablation study
  
  2.7 : Weight as parameter for Importance of features?


### 3. Post-processing: 
  
