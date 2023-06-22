# Machine_Learning_LinearRegression
Simple linear regression is a parametric test, meaning that it makes certain assumptions about the data.

Regression
The term regression is used when you try to find the relationship between variables.

In Machine Learning, and in statistical modeling, that relationship is used to predict the outcome of future events.

Linear Regression
Linear regression uses the relationship between the data-points to draw a straight line through all them.

This line can be used to predict future values.

How Does it Work?

Python has methods for finding a relationship between data-points and to draw a line of linear regression. We will show you how to use these methods instead of going through the mathematic formula.

In the example below, the x-axis represents age, and the y-axis represents speed. We have registered the age and speed of 13 cars as they were passing a tollbooth. Let us see if the data we collected could be used in a linear regression:

ExampleGet your own Python Server
Start by drawing a scatter plot:

import matplotlib.pyplot as plt

x = [5,7,8,7,2,17,2,9,4,11,12,9,6]

y = [99,86,87,88,111,86,103,87,94,78,77,85,86]

plt.scatter(x, y)

plt.show()

Result:

![image](https://github.com/Tejashripatil25/Machine_Learning_LinearRegression/assets/124791646/fb690285-b54a-4e53-831f-9266afcd903b)

