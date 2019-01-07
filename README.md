
# Sentiment Analysis of Google Play Store App Store reviews


## Executive Summary:
The sudden eruption of sentiment analysis, as well as opinion mining, has opened new possibilities to improve our information gathering interests. Generally it is seen that users make their decision to download the app based on various parameters like rating of the app, overall sentiment generated by the reviews of the app, price point of the application, i.e. whether the app is free or paid, the size of the app (it would seem people prefer apps that may be smaller in size as they occupy less space on their devices) etc. Also, the significance of these factors may vary based on the genre of the app i.e., whether the app belongs to the category lifestyle, food and drinks, health and fitness, books and reference, games and so on. Our endeavor in this project is to assess what is the effect of these parameters on the popularity of the app based on the app genre. We will use the number of downloads of the app as the popularity measure of our app.  

## Modelling and Exploratory Data Analysis:
We built a multi class logistic model to understand how different features and sentiments influence popularity of an app. We divided the apps into 3 popularity categories based on number of installs - low, medium and high. Based on the model, we see that the average rating of an app is a significant influencer of popularity. Between the average number of downloads vs overall app rating, the trend suggests that the average number of downloads per app increases consistently till the rating of 4.3 / 5.0,  indicating that apps with higher average rating have higher popularity and are more likely to be downloaded. That is visible from EDA of the data as well as the model.
Observations: 
From our analysis, we found that puzzles, photography, communication, shopping, entertainment apps have higher chances of being popular whereas simulation, weather, medical apps are less likely to have high downloads. 
For already popular apps, positive sentiment does not have an impact on likelihood of popularity, however for less popular apps, it is necessary to have positive reviews.

## Conclusions: 
In conclusion, we see how sentiment analysis can be used to find favourable features and problem areas for apps of different categories.
We also realised that the app reviews and positive sentiments play an important role in the initial phases of the app development but after achieving success, reviews do not have an impact.
App success also depends on the category of the app. We can use these findings and insights to build successful products. 
