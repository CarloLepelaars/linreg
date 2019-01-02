# linreg
Two different Linear Regression algorithms from scratch in Python.

Features two approaches:
1. Iteratively optimize the line of best fit and approximate the regression coefficent (m) and y-intercept (b).

2. Minimize the MSE (Mean Squared Error) through a formula and solve for the regression coefficent (m) and y-intercept (b). This approach is elegant and precise, but does not work well with large datasets. Other methods like gradient descent will be much more efficient on large datasets.

Formula for approach 2:
![](https://github.com/CarloLepelaars/linreg/blob/master/linreg_MSE_formula.png)


Inspiration comes from [Luis Serrano's explanation of Linear Regression](https://youtu.be/wYPUhge9w5c) and [DeepMind's Introduction to Tensorflow lecture](https://youtu.be/JO0LwmIlWw0).

Source of the formula image is [DeepMind's Introduction to Tensorflow lecture (32:31)](https://youtu.be/JO0LwmIlWw0?t=1951).
