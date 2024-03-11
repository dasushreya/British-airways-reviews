# British Airways Reviews Analysis
This project is the Data Science virtual Internship offered by Forage collaborated with British Airways. The main purpose of this project is to analyse the reviews given by british airways customers and provide insights regarding those reviews.

# The project is divided into 2 parts / tasks
Task 1 - Web scraping to gain company insights
Task 2 - Build a predictive model to understand factors that influence buying behaviour

# Task 1 - Web scraping to gain company insights.

I had scraped and collected the data which is the reviews or feedback of the British Airways’ customers from a website called Skytrax.  
The data included all the positive and negative feedback given by customers in their journey with British Airways and then analyzed the data, This process also included data cleaning as the data was bit messy.

I had to install many packages like numpy, pandas, requests, beautifulsoup and html5lib, matplotlib.pyplot, os, seaborn, wordcloud, nltk, spacy.

# Task 2 - Build a predictive model to understand factors that influence buying behaviour.

In this particular task, I had analysed the data set which was collected from task 1. And then trained a machine learning model to be able to predict the target outcome, which is a customer making a booking. After training the model, evaluated how well it performed by conducting cross-validation and outputting appropriate evaluation metrics. Furthermore, created a visualisation to interpret how each variable contributed to the model.

# Conclusion 

Task 1

Acoording to task 1, 
The total number of reviews were 3755, Reviews from various countries are 73, Overall rating given to British Airways services are 4.71 / 10.
By comparing all the graphs, we can conclude that most of the customers were satisfied with the cabin crew's services, as indicated by the majority of reviews, all of which were favorable. However, the majority of the customers were seated in business class as instead of economy class.Thus, looking it up, we can say that British Airways should focus more on enhancing economy class seating, entertainment, and service, as well as primarily delaying flights, as the majority of passengers had complaints about that.

Task 2,

According to task 2,
Chance of predicting true successful bookings is 59%, Precision score is 62%, Accuracy is 62% and Chance of predicting true incomplete bookings correctly is 66%.
I believe that I did not accurately predict the successful bookings. Although the imbalance dataset increases accuracy, it is unable to forecast successful bookings with any degree of accuracy. With 8,000 categorized as incomplete bookings and 7,000 as complete bookings, the dataset was balanced.





