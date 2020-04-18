## Definition:
## What is Linear Regression?
It is a relationship between 2 variables x and y where x = input or independent variables y = output or dependent value This relationship is in the form of a straight line that best tries to fit each variable.

Mathematically it can be defined as y = mx + c where x and y are as defined above, m = slope or coefficient of regression c = constant

General view of a straight line : y = mx + c

![](/images/line2.png)

## Best fit line
Let us see a real world graphical representation of Linear Regression. For this we are using SARS 2003 dataset provided by Kaggle.

Here, we are showing the data in the form of a scatter plot where the relationship between x and y variables is shown. To get better understanding of the relationship, we draw a line called as - best fit line. It is a line that is drawn through the scatter plot points. The idea of this line is to best fit all the points.
![](/images/bestfitline.png)

## Evaluation metrics:

### 1. Mean Absolute Error (MAE): 
The distance between any data point and the best fit line is called as prediction error. The absolute mean of it is called as Mean Absolute Error (MAE).

#### Value range: 
0 to ∞ Best value = 0.0 or we can also say that lower the value, better it is.

#### Formula:
![](/images/mae_formula.png)

### 2. Mean Squared Error (MSE): 
The summation of suqare of all the distances between any data point and the best fit line divided by the total number of data points (mean) gives us a value called as Mean Squared Error (MSE).

#### Value range: 
0 to ∞ Best value = 0.0 or we can also say that lower the value, better it is.

#### Formula:
![](/images/mse_formula.png)

### 3. Root Mean Squared Error (RMSE): 
For calculating RMSE, we do square root of MSE.

#### Value range: 
0 to ∞ Best value = 0.0 or we can also say that lower the value, better it is.

#### Formula:
![](/images/rmse.png)

Note: If MAE or MSE or RMSE value is 0 then it means that all the data points are on the best fit line. Higher the value means that the data points are away from the best fit line.

### 4. R2 Score - Coefficient of Determination: 
R2 Score is defined as regression sum of squares divided by the total sum of squares.

#### Formula  and all the parameters needed to calculate the value of R-square:
![](/images/r2_score.png)
OR
![](/images/r_square.png)

![](/images/r2_best_fit_line.png)

Consider the above example with one new line - horizontal added. So, now we can describe the formula components as -

a) SS (Res) = Regression sum of squares and it quantifies how far is the regression slope is from the horizontal (no relationship line) the sample mean or y¯.

b) SS (Tot) = Regression total sum of squares and it quantifies how much the data points, yi, vary around their mean, y¯.

