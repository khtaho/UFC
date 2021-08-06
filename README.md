## UFC Fight Predictor
![Header](https://github.com/khtaho/Projects/blob/main/ufc%20gloves_1.jpg "Header")

The UFC is a very interesting sport and there has been some statistics collected on sport since it first appearred in the 1990s.  

The dataset uses all the historical fight statistics from the very first UFC to 2021. Every elbow, takedown, KO, submission, head shot, significant strike and otehr moves have been recorded and in the data set. The goal of this project was to apply machine learning to help predict the outcome of future fights. 

### Let's look at some exploratory data!

![Header](https://github.com/khtaho/UFC_Predictor/blob/main/ag%20vs%20KOs%20WW.png "Header")

Looking at the chart above we can see the number of KOs by age for the welterweights. The fighters peak around the age of 27-28 for the most KOs.




![Header](https://github.com/khtaho/UFC_Predictor/blob/main/sig%20strikes%20vs%20KOs%20all%20weights%202.png "Header")

The chart above shows the number of significant strikes versus number of KOs for all the weight classes. The most number of KOs occur between 12 to 100 significant strikes. 

![Header](https://github.com/khtaho/UFC_Predictor/blob/main/sub%20histogram.png "Header")

The chart above shows the frequency of submissions at each round for  each weight class. The lightweights are the most talented submission artists.  Majority of submissions happen in the first round for most of the weight classes.

### Machine Learning
The machine learning model used sklearn's random forest and discovered the features that are significant to a fight outcome. Each weight class has different features that helped predict the outcome but the underlying theme for many of them were total strikes, number of head shots, significant strikes and percentage of significant strikes.

The regression model will predict future fight outcomes with just the names of the fighters, date of the fight and the weightclass.



