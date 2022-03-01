# [House Price Prediction: Project Overview](https://github.com/KrutikaDesai02/HousePricePrediction)
* Build a model that predict property price based on certain features such as bedroom, bathroom, sq feet, location etc. So, the task is to build a website using HTML/CSS/JavaScript that predicts estimated price for your house.
* In terms of project architecture, we are going to take a home set from Kaggle.com. Using that data set we will make a machine learning model. We are going to cover some data science concepts such as data cleaning, feature engineering, Dimensionality reduction, outliner detection etc.
* Before and after outliers removal: Rajali Nagar

 ![](/images/real1.png)
 
* Before and after outliers removal: Hebbal 

 ![](/images/real2.png)
 
* Histogaram after removing the outliers:

 ![](/images/real3.png)

* During model building we do GridSearchCV for hyperparameter tunning, k fold cross validation. For model building I used linear regression to achieve 84% accuracy.
* Once the model is built, we are going to export it to a pickle file and then we will write a python flask server which will consume this pickle file and do price prediction for us.
* This python flask server will expose HTTP endpoints for various requests and the UI written in HTML/CSS/JavaScript will make HTTP Get and Post calls.
* In terms of tools and technology we will use python as programming language, Pandas for data cleaning, Matplotlib for data visualization, Sklearn for model building, python flask for a back-end server, HTML/CSS/JavaScript for building our website.

 ![](/images/real4.png)
