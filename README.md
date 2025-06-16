# Employee-Sentiment-Analysis
PROJECT OVERVIEW

The goal of the project is to evaluate employee sentiment and engagement using data analysis techniques such as sentiment analysis, exploratory data analysis, sentiment labelling, employee ranking and predictive modeling. I need to analyze employee messages to understand how people feel and how engaged they are at work. I'll be working with raw data that doesn't have labels, so I will be figuring out the patterns myself using text analysis and statistics. The project has several different parts where I will analyze the data and build models to get insights.

PROJECT OBJECTIVE

The main goal is to evaluate employee sentiment and engagement by performing the following:
·	Sentiment Labeling: Automatically label each message as Positive, Negative, or Neutral.
·	Exploratory Data Analysis (EDA): Analyze and visualize the data to understand its structure and underlying trends.
·	Employee Score Calculation: Compute a monthly sentiment score for each employee based on their messages.
·	Employee Ranking: Identify and rank employees by their sentiment scores.
·	Flight Risk Identification: A Flight risk is any employee who has sent 4 or more negative mails in a given month.
·	Predictive Modeling: Develop a linear regression model to further analyze sentiment trends.



TOP EMPLOYEES BASED ON SENTIMENT SCORE

Top positive employees 2011-03:

patti.thompson@enron.com

rhonda.denton@enron.com

bobette.riner@ipgdirect.com


Top negative employees 2011-03:

johnny.palmer@enron.com

don.baughman@enron.com

eric.bass@enron.com



EMPLOYEES FLAGGED AS FLIGHT RISK

eric.bass@enron.com

lydia.delgado@enron.com


KEY INSIGHTS AND RECOMMENDATIONS
•	The logistic regression model predicts positive sentiments well (F1-score: 0.80, recall: 0.90). It struggles with negative sentiments—those are barely detected (F1-score: 0.00). The model may be biased due to class imbalance, with positives dominating.

•	Among these, only log_word_count showed a statistically significant effect (p < 0.001), with a positive coefficient of 0.86. This means that as the word count of an email increases, the likelihood of the sentiment being more positive also increases.

The model can be improved further by adding more features. As we can see the model has a weak fit on our data, this can be improved by adding more features to the data to make the model more reliable. We can also develop advanced feature engineering techniques such as squaring and interaction terms to further develop the model fit on our data.

