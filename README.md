# Logistic Regression Project 
In this project I have worked with a fake advertising data set, indicating whether or not a particular internet user clicked on an Advertisement on a company website. I have tried to create a model that will predict whether or not they will click on an ad based off the features of that user.

This data set contains the following features:

* 'Daily Time Spent on Site': consumer time on site in minutes
* 'Age': cutomer age in years
* 'Area Income': Avg. Income of geographical area of consumer
* 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
* 'Ad Topic Line': Headline of the advertisement
* 'City': City of consumer
* 'Male': Whether or not consumer was male
* 'Country': Country of consumer
* 'Timestamp': Time at which consumer clicked on Ad or closed window
* 'Clicked on Ad': 0 or 1 indicated clicking on Ad

**Read in the advertising.csv file and set it to a data frame called ad_data.**

## Exploratory Data Analysis

I've used seaborn to explore the data!

In the pairplots:
Now I can clearly see here that for some certain features the data in blue versus green here is actually quite seperate. which is a good indicator of certain things.

## Train Test Split to train the model

## In the end a Confusion Matrix and a Classification report is printed to show the result.

The model is doing pretty well with a 93% precision, recall and accuracy. 
There are very few mislabelled points which is not bad given the size of the dataset.

