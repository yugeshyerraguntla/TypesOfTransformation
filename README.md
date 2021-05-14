# TypesOfTransformation

This file has the types of Feature Transformation

Feature transformation is the process of modifying your data but keeping the information. These modifications will make Machine Learning algorithms understanding easier, which will deliver better results.


Types Of Transformation
	- Normalization And Standardization
	- Scaling to Minimum And Maximum values
	- Scaling To Median And Quantiles
	- Guassian Transformation
	- Logarithmic Transformation
	- Reciprocal Trnasformation
	- Square Root Transformation
	- Exponential Trnasformation
	- Box Cox Transformation
Each data point is replaced by its square root. Negative data is converted to positive by adding a constant, and then transformed. used for count data (data that follow a Poisson distribution) or small whole numbers.
Deatils of Transformations:

1. Standardization: Needed when features of input data set have large differences between their ranges, or simply when they are measured in different measurement units
2. Min-Max Scaling: It just scales all the data between 0 and 1. The formula for calculating the scaled value is - x_scaled = (x – x_min)/(x_max – x_min)
3. Median and Quan: Quantile Transformer Scaler converts the variable distribution to a normal distribution - scaler = QuantileTransformer()
4. Guassian       : 
5. Logarithamic   : Used to convert skewed distribution to normal distribution/less-skewed. Take the log of the values in a column and use them. df['x'] = np.log(df['x'])
6. Reciprocal     : Not sensitive to outliers. Removes median from data and scaled data by IQR
7. SquareRoot     : Each data point is replaced by its square root. Negative data is converted to positive by adding a constant, and then transformed. used for countdata or small.
8. Exponential    : 
9. Box-Cox	  : Transformation of a non-normal dependent variables into a normal shape. Box-Cox transformation does the best job at normalizing your skewed data.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

