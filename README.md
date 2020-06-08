#PROJECT  1: Real Estate(Zameen.com) Price Prediction


##PROBLEM:
Assume that you are a data scientist working for a real estate company such as zameen.com. Your business manager comes to you and asks you to build a model that can predict the property price  based on certain features such as no. of bedrooms, bathrooms, location etc.

##PROJECT ARCHITECTURE:
We will first build a model using sklearn and linear regression using zameen.com dataset from kaggle.com(link: https://www.kaggle.com/huzzefakhan/zameencom-property-data-pakistan). Second step would be to write a python flask server that uses the saved model to serve HTTP requests. Third component is the website built in HTML, CSS and Javascript that allows user to enter area, bedrooms etc and it will call python flask server to retrieve the predicted price.
