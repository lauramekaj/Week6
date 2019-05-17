# Creating plots using Python code
First uploading the library to create the plot is needed:
#import matplotlib.pyplot as plt
import numpy as np

After that when we want to calculate the mean value of the Load Vector we can find it through this code:
np.mean (Load_Vector)

To calculate to the standard deviation of the Load Vector:
np.std (Load_Vector)

# Creating plots using R code
After writing the matrix form of the given values we can create the plot by using this code:
plot (x,y,'l',main='System 420-7826.Load Vector',xlab='Time', ylab='Jobs in the System', 
col='blue', lwd=3)
Calculating mean value is as follows:
mean (y)
Calculating standard deviation through this code:
sd(y)

