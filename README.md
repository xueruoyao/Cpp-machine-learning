# C++ machine learning start from zero #<br/>
# 1 Linear Regression : #<br/>
## Use documents : LinearRegression.hpp, VectorOperations.hpp, test.cpp ##<br/>
## Record : ##<br/>
There we use single-variable function y = 3x + 4 to demonstrate the use of linear regression in consideration of simplicity. We use vector to store data as it's more flexible than the fixed-size array. We found that normalization is essential for the algorithm, without which gradient could growing incredibly fast because the calculation of gradient is associated with the variable x. At that time it's hard to control optimum learning rate. But in order to show the fitting function, we must give it up and just limit the input data x in a small range. What's more, there is another method to get the solution called Normal Equation, but we don't realise it here. To be honest, it is such attractive for me to study machine learning using C++.<br/>
### Finished on : 2021.10.6 ###<br/>
