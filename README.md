# IPL-match-prediction
A model has been developed to predict the outcome of a match using machine learning algorithms. For this purpose, Random Forest Classifier and Support Vector Machine classifier are used.

## Data Description
### matchdata ###
Data related to matches between 2008 and 2016 

### IPLmatch2019 ###
Data of 47 matches of IPL 2019

### twitterdata ###
Tweets of IPL matches

### finaldata ###
Data related to matches between 2008 and 2016 and sentiments calculated using tweets of a particular team on the day of match.

### Independent Variables: ### 
Season, Team1, Team2, Toss winner, Toss decision, Result, Win by runs, Win by wickets, dl applied, Player of the match, Venue, Umpire 1, Umpire 2, Sentiment
### Target Variable: ###
Winner Team

[Dataset Source](https://cricsheet.org/downloads/)


## Dependencies: ##
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* textblob
* tweepy
