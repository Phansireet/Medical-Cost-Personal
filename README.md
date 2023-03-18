# Medical-Cost-Personal

This project is the Linear regression model for medical cost dataset consisting of age, sex, BMI, children, smoker, and region and feature is the charges of insurance.

Linear regression is an algorithm used to predict the value of a variable based on the value of another variable.

In order to import the dataset, I used python's csv library to open and read the dataset file, which is .csv, and assign the BMI and feature into 2 arrays x,y.

After that, slope and intercept are calculated by x and y values using numpy's polyfit function. The polyfit function return a vector of coefficients p that minimises the squared error in the order deg, deg-1, … 0.

After that, I plotted the graph using x and y value and find the region under curve with this function.
```
def f(x):
    return slope * x + intercept
```

Detemine the range of Integration with 20 - 30 and calculated the integrate using scipy's quad function. The quad function return the integral of func from 20 to 30.

Finally, I plotted the area under the curve using matplotlib library
