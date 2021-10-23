# Titanic Data Exploration
## by Yahya Al-Balky


## Dataset

I used the 'train.csv' of the Titanic Dataset: https://www.kaggle.com/c/titanic/data

The data consisted of attributes of exactly 891 Titanic's passengers. The attributes included their id, name, economic class, sex, age, # of siblings/spouses aboard the Titanic, # of parents/children aboard the Titanic, fare, ticket number, cabin number, port of embarkation, and wether they survived or not.  I filled the missing values in 'Age' and 'Embarked' with the median and most-common value. I removed three data points from the analysis due to them being outliers. I removed the id, name, and ticket number features due to irrelevancy to our analysis, and removed cabin number due to a lot of missing information.

## Summary of Findings

In the exploration, firstly I found out that the dataset was un-balanced (only ~38.4% survived). I found out that most of the passengers where males (around 65%), and that most of the passengers where from the lower class (around 55%). I found out that most of the passengers paid a low fare, and discovered two peaks in the log-scale distribution of the passenger fare (one between 6 and 10, and a second little below 30). I found a high negative correlation between the passenger's economic class and fare, and a correlation between both of them and the passenger's chance of survival. I found out an axiomatic relation between the # of parents/children aboard the Titanic and # of siblings/spouses aboard the Titanic.

The most interesting finding was that after finding out that the survival rate among females was way higher than among males (only about 25% of the males survived, while about 65% of the females survived!), I found out that this assumption only applied for passengers from the lower class and for passengers that embarked from Southampton or Queentown, while the survival rate among females for passengers from the middle or upper class or passengers that embarked from Cherbourg was actually much lower than that of males.


## Key Insights for Presentation

For the presentation, firstly I point out to the unbalance in our data (with changing the x-axis label for a more clear presentation of the feature's values). Then I plot the log-scale distribution of passenger fare with pointing out to the multimodal shape. I then present the heatmap of pairwise correlations amond features pointing out to the correlation between both the passenger fare and his/her economic class with the chance of survival. Finally, I present our most significant finding regarding the survival rate among females vs males and how it differs by economic class and port of embarkation using several multi-variate plots.
I also titled all of the plots used in the presentation with the suitable title for each one.
