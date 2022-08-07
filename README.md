# Linear-Regression-with-Numpy
_________________________

## Course Objectives
In this course, we are going to focus on three learning objectives:

1. Implement the gradient descent algorithm from scratch.
2. Perform univariate linear regression with Numpy and Python.
3. Create data visualizations and plots using matplotlib.

By the end of this course, you will be able to build linear regression models from scratch using NumPy and Python, without the use of machine learning frameworks such as scikit-learn and statsmodels.

## Course Structure
This course is divided into 3 parts:

1. **Course Overview**: This introductory reading material.
2. **Linear Regression with NumPy and Python**: This is the hands on project that we will work on in Rhyme.
3. **Graded Quiz**: This is the final assignment that you need to pass in order to successfully complete the course and earn a Course Certificate.

## Project Structure
The hands on project on Linear Regression with NumPy and Python is divided into the following tasks:

### Task 1: Introduction and Import Libraries
- Introduction to the data set and the problem overview.
- See a demo of the final product you will build by the end of this project.
- Introduction to the Rhyme interface.
- Import essential modules and helper functions from NumPy and Matplotlib.

### Task 2: Load the Data and Libraries
- Load the dataset using pandas.
- Explore the pandas dataframe using the head() and info() functions.

### Task 3: Visualize the Data
- Before starting on any task, it is often useful to understand the data by visualizing it. 
- For this dataset, we can use a scatter plot using Seaborn to visualize the data, since it has only two variables: the profit and population.

### Task 4: Compute the Cost $𝐽(\theta)$
- Let’s now take a look at the machinery that powers linear regression: Gradient Descent.  
- We want to fit the linear regression parameters $\theta$ to our dataset using gradient descent.
- The objective of linear regression is to minimize the cost function $J(\theta)$.
- You can think of the cost as the error your model made in estimating a value.

### Task 5: Implement Gradient Descent from scratch in Python
- Recall that the parameters of our model are the $\theta_j$ values. 
- These are the values we will adjust to minimize the cost $J(\theta)$. 
- One way to do this is to use the batch gradient descent algorithm.
- In batch gradient descent, each iteration performs the following update. 
- With each step of gradient descent, the parameters $\theta_j$ come closer to the optimal values that will achieve the lowest cost $J(\theta)$. 

### Task 6: Visualizing the Cost Function $J(\theta)$
- To better understand the cost function $J(\theta)$, we will plot the cost over a 2-dimensional grid of $\theta_0$ and $\theta_1$ values.
- The purpose of this graph is to show you how $J(\theta)$ varies with changes in $\theta_0$ and $\theta_1$. 
- We can see that the cost function $J(\theta)$ is bowl-shaped and has a global minimum. 

### Task 7: Plotting the Convergence
- Let’s plot how the cost function varies with the number of iterations. 
- When we ran gradient descent previously, it returns the history of $J(\theta)$ values in a vector "costs". 
- We will now plot the J values against the number of iterations. 

### Task 8: Training Data with Univariate Linear Regression Fit
- Now that we have correctly implemented and run gradient descent and arrived at the final parameters of our model, we can use these parameters to plot the linear fit. 

### Task 9: Inference using the optimized $\theta$ values
- In this final task, let’s use our final values for $\theta$ to make predictions on profits in cities of 35,000 and 70,000 people. 
