# Introduction

The present lab session introduces the *Gradient Descent* optimization method using data form a linear model. First, the student will understand the procedure to compute the *Gradient* of the Mean Squared Error (MSE) and how to update the model parameter iteratively. 

Then, the model parameters are updated iteratively by applying:

$$\theta_{N}=\theta_{old}-\eta \nabla MSE(\theta)$$

Next, the student will implement the GD optimizer inside a `for` loop to limit the number of iteration. Finally, a function is implemented to visualize the learning steps and observing by plots, how the parameters adjust the model.

# Objectives

## General objective

To implement the **Batch-Gradient Descent** optimization method using the Gradient Descent equation in Linear models. 

## Specific objectives

- Implement the Gradient
- Test the Batch-Gradient Descent algorithm by steps
- Implement the BGD in a `for` loop
- Develop a function to plot the BGD by passing the parameter: learning rate, number of iterations, number of data point to train the model
- Implement a function or script to determine the MSE considering: learning rate, number of iterations, number of points; $MSE(\eta,ni,m)$


**Note:** you can check this direction formatted in a Readme file by visiting the its [github-page](https://github.com/ITM-AI/3-gradient-descent-directions)


Formato para el reporte: https://www.overleaf.com/latex/templates/formato-reporte-ingenieria/vzkwrzrryfqm
