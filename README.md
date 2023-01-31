# House-Price-Prediction

 ## **1. Introduction**
 
**1.1 Aim and Objective of the Project:**

A home is a basic necessity for everyone living in the world, and humans want it to be a perfect place for their kids to grow, to spend their lifetime in peace at the place they wish to have all the wonderful amenities. The demand for house is increasing gradually depending upon the population. And, as we talk about buying a House not all human beings want to buy/ own a lavish home. But they surely need a house with their desired amenities in the chosen surroundings. The problem here is to predict the House Prices based on an individual like and dislikes.The objective of the project is to perform data visualisation techniques to understand the insight of the data. Machine learning often required to getting the understanding of the data and its insights. This project aims apply various Python tools to get a visual understanding of the data and clean it to make it ready to apply machine learning and deep learning models on it. Validate the model’s prediction accuracy. Identify the important home price attributes which feed the model’s predictive power.

**1.2 About domain:**

Housing prices are an important reflection of the economy, and housing price ranges are of great interest for both buyers and sellers . Ask a home buyer to describe their dream house, and they probably won’t begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition’s data-set proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

So here we have data set which have various other factors in mind other than no. of rooms and height of the house . 
This problem involves predicting the prices of the houses which are continuous and real valued outputs. Thus, this is a Regression Problem.
It also Predict the sale price for each house and minimise the difference between predicted and actual rating . The work flow of the project is some what like this  :
House dataset importing 
Data pre-processing 
Data analysing 
Train Test split 
Using XGBoost Regressor Model for prediction
Evaluation
The project also compares the accuracy of the predicted price and the actual price on the following data set imported using R squared error and Mean absolute error.

**1.3 Problem Specification:**

Having lived in India for so many years if there is one thing that I had been taking for granted , it’s that housing and rental prices continue to rise. Since the housing crisis of  2008, housing prices have recovered remarkably well, especially in major housing markets. However, in the 4th quarter of 2016, I was surprised to read that Bombay housing prices had fallen the most in the last 4 years. In fact, median resale prices for condos and coops fell 6.3%, marking the first time there was a decline since Q1 of 2017. The decline has been partly attributed to political uncertainty domestically and abroad and the 2014 election. So, to maintain the transparency among customers and also the comparison can be made easy through this model. If customer finds the price of house at some given website higher than the price predicted by the model, so he can reject that house.


## **2. Literature review and Prior Art Search**

**2.1 Observation done by the group:**

According to current observation done by our group, there are many individuals who struggle for finding the price of the house according to the current situations in the society   So, we decided to make a project that can predict the price of the houses located to a particular area according to various factors in the dataset . As our domain is a backend project which predicts the price of the house by some factors and the machine learning algorithm , so no field work or any physical interactions were done so all these observations were done through means of online study.  

**2.2 Literature Survey:**

House price prediction is a vast topic, which is implemented through a variety of Computer Science Methods. Like Machine Learning, Linear Regression, Decision Tree, Deep Learning, Fuzzy Logic, ANFIS (Adaptive-Neuro Fuzzy Inference System), and Linear performance pricing.
In proposed model of Machine Learning, the dataset is divided into two parts: Training and Testing. 80% of data is used for training purpose and 20% used for testing purpose. The training set include target variable. The model is trained by using various machine learning algorithms, out of which Random forest regressions predict better results. For implementing the Algorithms, they have used Python Libraries NumPy and Pandas.
In another paper based on Machine Learning has used the multivariate linear regression model to perform the prediction. Also, it is compared with other Machine Learning models like Lasso, LassoCV, Ridge, RidgeCV and decision tree regressor. Multivariate linear regression and LassoCV performs the best with 84.5% accuracy.
Our model is works on decision tree regression (XGBoost Regression) .

**Libraries Used for this Project include –**
 
 1)Pandas
 
 2)NumPy
 
 3)Matplotlib
 
 4)Seaborn
 
 5)Scikit Learn
 
 6)XG Boost
 
 
 
 ## Model Used 
 
  **XG Boost Regressor Model**
  
• XG Boost stands for eXtreme Gradient Boosting.

• The XG Boost library implements the gradient boosting decision tree algorithm.

• Boosting is an ensemble technique where new models are added to correct the errors made by existing models.

Models are added sequentially until no further improvements can be .

