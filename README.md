Linear Regression with NumPy and Python

In this project, I am going to focus on three learning objectives:

- Implement the gradient descent algorithm from scratch.
- Perform univariate linear regression with Numpy and Python.
- Create data visualizations and plots using matplotlib.


By the end of this project, I was able to build linear regression models from scratch using NumPy and Python, without the use of machine learning frameworks such as scikit-learn and statsmodels.


The project on Linear Regression with NumPy and Python was divided into the following tasks:

- Task 1: Introduction and Import Libraries
        Introduction to the data set and the problem overview.
        Import essential modules and helper functions from NumPy and Matplotlib.

- Task 2: Load the Data and Libraries
        Load the dataset using pandas.
        Explore the pandas dataframe using the head() and info() functions.

- Task 3: Visualize the Data
        Understand the data by visualizing it.
        For this dataset, I will use a scatter plot using Seaborn to visualize the data, since it has only two variables: the         profit and population.
- Task 4: Compute the Cost 𝐽(𝜃)
        A look at the machinery that powers linear regression: Gradient Descent.
        I want to fit the linear regression parameters 𝜃 to my dataset using gradient descent.
        The objective of linear regression is to minimize the cost function J(𝜃).
        We can think of the cost as the error my model made in estimating a value.
- Task 5: Implement Gradient Descent from scratch in Python
        The parameters of my model are the 𝜃_j values.
        These are the values I will adjust to minimize the cost J(𝜃).
        One way to do this is to use the batch gradient descent algorithm.
        In batch gradient descent, each iteration performs the following update.
        With each step of gradient descent, the parameters 𝜃_j come closer to the optimal values that will achieve the lowest           cost J(𝜃).
- Task 6: Visualizing the Cost Function J(𝜃)
        To better understand the cost function J(𝜃),I will plot the cost over a 2-dimensional grid of 𝜃_0 and 𝜃_1 values.
- Task 7: Plotting the Convergence
        Plotting how the cost function varies with the number of iterations.
        When I ran gradient descent previously, it returns the history of J(𝜃) values in a vector “costs”.
        I will now plot the J values against the number of iterations.
- Task 8: Training Data with Univariate Linear Regression Fit
        Now that I have correctly implemented and run gradient descent and arrived at the final parameters of my model, I    can use these parameters to plot the linear fit.
- Task 9: Inference using the optimized 𝜃 values
In this final task, I will use my final values for 𝜃 to make predictions on profits in cities of 35,000 and 70,000 people.

