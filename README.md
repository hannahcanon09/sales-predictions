# sales-predictions

# Sales Prediction

Sales Prediction involves forecasting the quantity of products customers will purchase, considering factors such as price, sales and such. The dataset has 12 features and 8523 rows. 

## Overview 

With the target of predicting item outlet sales, this becomes a regression problem. The dataset underwent exploratory data analysis, visualizations and preprocessing. Two models were used, namely Linear Regression Model and Random Forest Regressor. The models were compared using its Correlation Coefficient (R2) and its root mean squared error (RMSE). 

## Visualizations

Heatmap
Outlet_Identifier and Item_Outlet_Location_Type have the strongest correlation with a negative correlation of -0.72 

As for our target variable, Item Outlet Sales, Item_MRP has the highest correlation to it with a moderate positive correlation of 0.57. For the purpose of this presentation, we will focus on the variable with the highest correlation to the target variable, Item Outlet Sales. 

Histogram of Item Outlet Sales
The histogram of Item Outlet Sales in USD is right skewed. This means that the data is concentrated on the left with a tail on the right. This means that some stores have better sales than most. The stores with sales in the concentrated area can employ similar strategies than those on the right tail to improve their sales.

Boxplot of Item MRP
The Boxplot of Item MRP shows a no skew, meaning its distribution is symmetrical. The data points in this column are consistently distributed across, resulting in stability. Furthermore, the average of Item MRP is also equal to its median. It also has no visible outliers.


## Recommended Model: Random Forest Regressor Model

The Linear Regression model seems to overfit severely on the test data, as evident from the extremely poor R² and high RMSE. It might not generalize well to unseen data.

The Random Forest Regressor performs significantly better than Linear Regression. It shows strong performance on the training data, capturing almost 94% of the variability. However, there is a drop in performance on the test data, indicating some degree of overfitting or inability to generalize perfectly to unseen data, which is common with complex models.

Overall, based on the provided evaluation metrics, the Random Forest Regressor appears to be a better model choice between the two, despite its slight performance drop on the test set compared to the training set. It seems to generalize better to unseen data compared to the Linear Regression model.


## Acknowledgments

Any contributions are welcomed!

