# Data Science Projects
# [Project 4: Foliar Diseases Classification](https://github.com/datascientist-hist/Foliar-Diseases-Classification)

**Goal**

Identify the category of foliar diseases in apple trees

**Status**

Work in Progress

# [Project 3: Crimes in Italy Dashboard](https://github.com/datascientist-hist/Crimes-in-Italy-Dashboard) 

**Project done with my colleague  Orazio Pontorno**

The first Dashboard focuses on the distribution of crimes in Italy

![](/images/DASH1.png)

**[See the project to obtain more detail!](https://github.com/datascientist-hist/Crimes-in-Italy-Dashboard)**


# [Project 2: Soccer Results Classification](https://github.com/datascientist-hist/Football-Results-classification) 

**Goal**

*Championship used Serie A Year 2021/2022*

The aim of this project is to try to classify if a game is going to end with a number of goal greater than 2, to carry out this task i will download a dataset where are present a lot of features as number of goal,team names and stats related to matches, are also present the odds provided by bookmaker BET365 that can be converted into probabilities and can be used as referencee point ,but my purpose would be beating those odds.

The strategy that i want to adopt is based on goals scored and goals conceded:

- I will compute the average goals scored and conceded for each team from all the previous matches

- and the average goals scored and conceded for each team from the the last n previous matches (that it can be 1 or 2 and so on..)

I would like to find useful differences between the performance of teams in the last n previous games and the performance in the total games, to classify the target

**Results**

|Model|Accuracy|Precision Score Over 2.5|Precision Score Under 2.5|
|-----|--------|------------------------|-------------------------|
|Bookmaker|61.46%|60.00%|66.66%|
|Random Forest| 60.55%| 66.66%|55.73%|
|Tuned Randome Forest|60.55%|68.18%|55.38%|


![](/images/confmatrixtest.png)


# [Project 1: Spam email Classification](https://github.com/datascientist-hist/Spam_Messages_Classification)

![](/images/email-spam.png)

## Goal

The aim of this project is to classify emails into spam and ham emails.  
To do this I will use the frequencies method that will count  how many different words there are in a sentence after that I will choose a number of relevant words.[Below I will expalin better the method](https://github.com/datascientist-hist/Spam_Messages_Classification)


## Results

Feature Importance         |  Misclassification table
:-------------------------:|:-------------------------:
 ![](/images/featureimportance.png)  |   ![](/images/misclassification.png)


