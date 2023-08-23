# Car Price Prediction
In this project I'm trying to analyze the used car prices from dataset available at https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data in order to predict the most probable car price.
It is mainly divided into four parts:-
- Data Wrangling

- Exploratory

- Model Development

- Model Review and Evaluation

# Softwares and Libraries Used:

 - Anaconda Distribution
- Jupyter Notebook

- Numpy
- Pandas
- Matplotlib
- Seaborn

# Importing Modules
 - import pandas as pd
 - import numpy as np
 - import math
 - import matplotlib.pyplot as plt
 - import seaborn as sns
 
 # Analysis
  - Histograms representing Binned prices in Low, Medium, High.

![histograms](https://user-images.githubusercontent.com/96294707/170836603-1148b008-9d65-4d9d-b3c6-5beb619781dd.png)

  - Boxplots representing effect of wheel frive with prices.
  
 ![boxplots](https://user-images.githubusercontent.com/96294707/170836677-39107ad9-2be8-4e5f-a547-8a5d6fe4f4a6.png)
 
  - Scatter plot for Prices over Engine size
 
![scatter](https://user-images.githubusercontent.com/96294707/170836735-66f5844c-07c7-4cc6-a5b9-e61bb2227dd5.png)

  - Linear Relationship between engine size and price
  
![positivelinear](https://user-images.githubusercontent.com/96294707/170836812-dea3c69c-acaf-436a-9df5-60f5ee2748d2.png)

  - Linear Regression plot
  
![Figure_2](https://user-images.githubusercontent.com/96294707/170836972-7e905bbc-50cf-4536-bcf8-d6b8d08a8d98.png)

  - Multiple Regression plot
 
 ![Figure_1](https://user-images.githubusercontent.com/96294707/170837002-438bdef7-829a-4ddb-8bf4-f55ea4826917.png)



 # Conclusion
 
 The distribution plot of Linear Regression and Multiple Regression technique shows how the model predicts the prices of automobiles based on "horsepower", "curb-weight", "engine-size" and "highway-mpg"

Comparing these three models, we conclude that the MLR model is the best model to be able to predict price from our dataset.
