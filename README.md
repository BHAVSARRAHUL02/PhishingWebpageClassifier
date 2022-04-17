# PhishingWebpageClassifier

Web service is one of the key communications software services for the Internet. Web phishing is one of many security threats to web services on the Internet. Web phishing aims to steal private information, such as usernames, passwords, and credit card details, by way of impersonating a legitimate entity or faking to be a Legitimate entity(ex - www.googlle.com). It will lead to information disclosure and property damage. This projects mainly focuses on applying a machine learning framework to detect phishing websites using the data set provided on the kaggle app of the this particular project.

# What we are Doing ?

We have dataset that contains metadata about 5000 legitimate and 5000 phishing sites. Phishing is type of semantic attack, often used to steal user sensitive information including login credentials and credit card numbers by masquerading as a trusted entity, enticing victim into clicking on link or opening an attachment in an email or instant message from whatsapp,facebook. Here we use large dataset with many metadata information, for which we might have to understand the meaning of the metadata before working on dataset.( ex - Numdots, Numdash, NumPercent, NoHttps etc.)

# Machine learning we used in our Project

So we start of with building machine learning model - To get diversity in Prediction we use a “Ensemble Learning” to train that dataset using phishing site data points with different models of classification.we use RandomforestClassifier. LogisticRegression, KNN models to train the model.There is abundant information - metadata of the sites which helps in recognizing the phishing sites.in the particular project we will learn how to cleansed the dataset by removing the outliers, white space if the data
points have and then we can use that cleansed data to train the model

# Project Requirement 

ML model ( packages ) - NUMPY, PANDAS, SEABORN, MATPLOTLIB
Framework - Django for integration with ML model & Website
Website - HTML,CSS,JAVASCRIPT
