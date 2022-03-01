# HousePricePrediction
# [House Price Prediction: Project Overview](https://github.com/KrutikaDesai02/HousePricePrediction)
* Build a model that predict property price based on certain features such as bedroom, bathroom, sq feet, location etc. So, the task is to build a website using HTML/CSS/JavaScript that predicts estimated price for your house.
* In terms of project architecture, we are going to take a home set from Kaggle.com. Using that data set we will make a machine learning model. While building the model we are going to cover some data science concepts such as data cleaning, feature engineering, Dimensionality reduction, outliner detection etc.
* Based on different scatter plot charts we can see that data points highlighted in red below are outliers and they are being removed.
![](/images/1%20tbr52QE8lXy60Ta-zOqsbA.png)
![](/images/1%20rVSk8IsLuNwgtU8zgEAtkw.png)
* Once the model is built, we are going to export it to a pickle file and then we will write a python flask server which will consume this pickle file and do price prediction for us.
* This python flask server will expose HTTP endpoints for various requests and the UI written in HTML/CSS/JavaScript will make HTTP Get and Post calls.
* In terms of tools and technology we will use python as programming language, Pandas for data cleaning, Matplotlib for data visualization, Sklearn for model building, python flask for a back-end server, HTML/CSS/JavaScript for building our website.
![](/images/1%20AqpJttBeVD5wLXIcnwWZHA.png)
