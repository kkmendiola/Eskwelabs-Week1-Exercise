# Eskwelabs-Week1-Exercise
Eskwelabs, Week1, Exercise 1 and 2: Data Science - Getting Started with Python

Exercise 1 - A bit of Math

For these "word" problems, use Python to clearly solve them. Your code will "show your work" - use good variable names! To show your answers you should write a print() statement at the end.
a) It's a gas

A taxi driver is calculating their profit over two weeks by adding up the fares they charge and subtracting the cost of gas. The price of gas changes over time - it was $3.52/gallon the first week and $3.57/gallon this second week. Their car gets 20 miles per gallon.

For the first week the driver had a total of 23 passengers with average $29 fare each, and drove a total of 160 miles. For the second week they had 17 passengers with average $30 fare each, and drove a total of 220 miles. Assume that for both weeks they purchase all the gas needed during that week (i.e. they refuel every week to maintain a constant level of gas in the tank).

Based on the above, answer the following questions:

    What is their total profit over both weeks?
    During which week was their average (mean) profit per passenger higher?

b) Mo' money...

A cash drawer contains 160 bills, all 10s and 50s. The total value of the 10s and 50s is $1,760.

How many of each type of bill are in the drawer? You can figure this out by trial and error (or by doing algebra with pencil and paper), but try to use loops and conditionals to check a plausible possibilities and stop when you find the correct one.

Exercise 2 - Drawing a plot

Use NumPy and Matplotlib to draw a scatterplot of uniform random (x, y) values all drawn from the [0, 1] interval. Helpful documentation:

    https://matplotlib.org/tutorials/index.html
    https://docs.scipy.org/doc/numpy/user/quickstart.html

Stretch goal - draw more plots! You can refer to the Matplotlib gallery for inspiration, but don't just reproduce something - try to apply it to your own data.

How to get data? There's many ways, but a good place to get started is with sklearn.datasets:

from sklearn import datasets
dir(datasets)
