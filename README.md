# Weight_Prediction
Weight Prediction is a model which predicts weight based on their height and the algorithm used here is linear regression.

**Objectives:-**  Predict the weight based on height.
<br />**Software Used:-** Anaconda, Jupyter Notebook, pyqt5
<br />**Algorithm Used:-** Linear Regression Algorithm
<br />**Definition:-** Linear Regression is a machine learning algorithm based on supervised learning. It performs a regression task. Regression models a target prediction value based on independent variables. It is mostly used for finding out the relationship between variables and forecasting.
<br />**How to:-**
<br />1. Read the csv file using pandas opencv() function.
<br />2. Divide the dataset into x and y, where x having input values and y having outputs value.
<br />3. Initialize the model by importing Linear_Model from sklearn.
           <br />-> import sklearn
          <br /> -> from sklearn import linear_model
<br />4. Train the model.
          <br /> -> model=linear_model.LinearRegression() 
          <br /> -> model.fit(x,y)
<br />5. Predict the weight by taking height user input.

**OUTPUT**



