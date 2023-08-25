# ***`onenonly.stats` Module, part of One-n-Only python package***

## ***This repository contains a set of mathematical functions implemented in Python. These functions can be used to perform various statistical calculations and mathematical operations. The functions are designed to work with arrays or lists of numerical values.***

### ***Functions Included***

***`mean(array: list)`***  
Calculates the mean (average) of the values in the input array.  

***`median(array: list)`***  
Calculates the median of the values in the input array.

***`mode(array: list)`***  
Calculates the mode(s) of the values in the input array.

***`Range(array: list)`***  
Calculates the range of the values in the input array.

***`variance(array: list, kind: str="sample")`***  
Calculates the variance of the values in the input array. The kind parameter specifies whether to use "sample" or "population" variance formula.

***`standardDeviation(array: list, kind: str="sample")`***  
Calculates the standard deviation of the values in the input array. The kind parameter specifies whether to use "sample" or "population" standard deviation formula.

***`quartile(array, percentile)`***  
Calculates the quartile value at the specified percentile for the input array.

***`mse(actual: list, predicted: list)`***  
Calculates the Mean Squared Error (MSE) between the actual and predicted values.

***`rmse(actual: list, predicted: list)`***  
Calculates the Root Mean Squared Error (RMSE) between the actual and predicted values.

***`errors(actual: list, predicted: list)`***  
Calculates the errors between corresponding elements of the actual and predicted arrays.

***`meanError(actual: list, predicted: list)`***  
Calculates the mean error between actual and predicted values.

***`meanAbsError(actual: list, predicted: list)`***  
Calculates the mean absolute error between actual and predicted values.

***`confusionMatrix(actual: list, predicted: list)`***  
Calculates the confusion matrix between actual and predicted class labels.

***`accuracy(yActual: list, yPredicted: list)`***  
Calculates the accuracy between actual and predicted class labels.

***`correlationCoef(x: list, y: list)`***  
Calculates the correlation coefficient between two arrays x and y.

***`movingAvg(array: list, window: int)`***  
Calculates the moving averages of the input array using a specified window size.

***`expMovingAvg(array: list, alpha: float)`***  
Calculates the exponential moving averages of the input array using a specified smoothing factor alpha.

***`distance(array1: list, array2: list, kind="euclidean")`***  
Calculates the distance between two arrays using either the Euclidean or Manhattan distance.

***`gradientDescent(x, y, learning_rate=0.01, epochs=1000)`***  
Performs gradient descent to find the best-fit slope and intercept for a linear regression model.

### ***Usage***  

```python
from onenonly.stats import mean,median,mode,Range
x = [27, 95, 53, 64, 39, 39, 75, 21, 67, 64, 96]
print(mean(x)) # 58.18181818181818
print(median(x)) # 64
print(mode(x)) # [39, 64]
print(Range(x)) # 75
```
