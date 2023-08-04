# What is the cause for Higher Sales.

We created many different graphs and data columns to determine this.

Author: Joshua Rohn

# Business problem:

Trying to find a reason for the end of season sales and how can it be improved.

# Data:

The data is taken from 'sales_predictions_2023.csv'

# Methods:

We cleaned the data with no leakage. The graphs are one variable and then two variable with the target variable Outlet_Sales as the second variable.

# Visuals:

Item Visibility vs Item Outlet Sales

![download](https://github.com/jrohn34/Prediction-of-Product-Sales/assets/138350298/40523282-5a54-4483-be20-afd2d5c96056)

It could appear that there is a corralation between item visibility and sales but I believe that this graph does not show the whole picture. There are less data points at the end of the graph showing that it is skewed to the beginning of the graph where there is more data there. 

Outlet_Type vs. Item_Outlet_Sales

![download-1](https://github.com/jrohn34/Prediction-of-Product-Sales/assets/138350298/e78a60d4-2dbf-4a72-833c-85174a15b900)

Here we see that there is a correlation between the type of market and sales. We see that Grocery sales are lacking and we see that the super market type 1 is the same as type 2 but type 1 has a lot more locations so it is doing worse than the other super markets. The best out of the four would be super market 3.

# Model:

The model that is going to be used is the tuned random forest model. 

The the tuned random Forest model the R-Squared value of .6171 and the RMSE is 1020.2148

The tuned random forest model can provide accurate predictions of the sales, although the predictions are not finite so they can change and should not be looked at as a definite outcome more as a estimation. 


# Recommendations:

That we continue to moniter these variables and maybe add new variables to determine if there is anymore factors into the sales increase or decrease. 

# Limitations & Next Steps:

The next steps would be to continue to moniter other catagories and see if it has correlation with sales. 

# For further information:

For any additional questions, please contact rohnjosh19@gmail.com
