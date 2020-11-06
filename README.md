# Data Science Nigeria 2020 AI Bootcamp Qualification Competition
A copy of my solution to the Bootcamp qualification competition

Position on Leaderboard -- (top 20%)

link -- https://zindi.africa/hackathons/dsn-ai-bootcamp-qualification-hackathon

# KOWOPE MART Loan Prediction Competition

Kowope Mart is a Nigerian-based retail company with a vision to provide quality goods,education and automobile services to its customer at affordable price and reduce if not eradicate charges on card payments and increase customer satisfaction with credit rewards that can be used within the Mall. To achieve this the company has partnered with DSBank on co-branded credit card with additional functionality such that customers can request for loan, pay for goods even with zero-balance and then pay back within an agreed period of time. This innovative strategy has increased sales for the company. However, there has been recent cases of credit defaults and Kowope Mart will like to have a system that profiles customers who are worthy of the card with minimum if not zero risk of defaulting.

You have been employed as a Data Scientist to leverage Machine Learning to predict customers who are likely to default or not.

# Predict customers who will default on loan
# My Solution Approach
* A Catboost model
  * Used a Kfold of 10 splits
  * Tuned parameters a little
* Voting Classifier of Catboost models and LGBM 
  * Used a Kfold of 10 splits
  * Tuned parameters of the Catboost models a little
* Voting Classifier of Catboost models and LGBM
  * Engineered new features
  * Dropped some features
  * Used a Kfold of 10 splits
  * Tuned parameters of the Catboost models a little
* Created a blend model of the three models
