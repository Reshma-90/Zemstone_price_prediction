# Zemstone_price_prediction
This repository contains code for building a Linear Regression model to predict price of a zem stone.
# Goal of this project:
The goal of this model is to predict price of a new stone according to its feature.
- The data set here conatains around 30000 zem stone feature details about its size,type of cut along with price of stone.
# Head of the data set:
![image](https://user-images.githubusercontent.com/95558910/147411808-8e116610-c911-49d3-bef8-941e63887fc4.png)
# Data Description:
![image](https://user-images.githubusercontent.com/95558910/147411828-2dff8a10-72d3-49a0-a5f3-64546d30d3e1.png)
# EDA
- All preprocesseing steps like checking missing values,duplicate values,random error checking,outliers checking were performed and necessary steps taken.
- An Exploratory Data Analysis were performed on the dataset by doing univariate,bivariate and multivariate analysis.
- From EDA some insights were noted down.
# Data Encoding
- The catgorical values were converted to dummy variables.
# Data Splitting
- The dataset were splitted into 70:30 ratio of 70% of data as train set and rest 30% as test set.
# Model bulding
- In total four models were build a statistical linear regression model and another using sklearn.Two reguralized models Lasso and ridge were also build.
# Performance Check  
- The model performance of the models were checked by finding R-squared,Adjusted R-squared and Root mean Squared values.
# Model comparision:
- All the models were compared on the performance metrics. 
![image](https://user-images.githubusercontent.com/95558910/147412228-d82b5ff6-4b84-4bae-ad5d-f1f191f2ed30.png)
# Visualizing Model performance
- The model performance were visualized on the basis of adjusted R-squared on test data.
![image](https://user-images.githubusercontent.com/95558910/147412192-f2420d0e-c600-47ab-a709-2e04f577b79c.png)
# Final model selection:
- It has been observed that statistical Linear Regression model performed slightly better than models. Hence it has been selected as the final one for this data.
