# polyfit

This is a stand alone C++ program to fit a curve with a polynomial.

To compile: g++ -o Polyfit Polyfit.cpp

Inputs:

k: Degree of the polynomial
fixedinter: Fixed the intercept (coefficient A0)
wtype: Weight: 0 = none (default), 1 = sigma, 2 = 1/sigma^2
alphaval: Critical apha value
x[]: Array of x values to be fitted
y[]: Array of y values to be fitted
erry[]: Array of error of y (if applicable)


