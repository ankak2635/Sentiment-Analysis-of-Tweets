# Sentiment-Analysis-of-Tweets
Explores and runs a sentiment analysis using VADER approach on about 25k tweets mentioning @Dell to label each tweet as either positive, negative or neutral.

VADER (Valence Aware Dictionary and sEntiment Reasoner)

* Uses "bag of words" approach
    1. Removes stop words
    2. each word is scored and combined to give a total score
    3. However, this model does not account for the relations between texts
    
**Steps & Modules:**

* pandas - Performs EDA
* matplotlib and seaborn - visualization
* nltk’s SentimentIntensityAnalyzer- - runs VADER model
* Labels tweets as positive, negative or neutral
* wordcloud - to build wordcloud
* Interesting insights from further EDA

This is work in progress notebook, more analysis to come! 
Thanks
