# Natural Language Processing with Disaster Tweets

Twitter has become one of the most popular sources of information. 
In particular, it has become an important communication channel in emergencies 
that works in real time. 
Therefore it is of great interest to be able to analyze a tweet and determine if it is reporting an emergency (disaster) or not.

Goal: Read tweets and classify them into 2 classes: disaster or no disaster.

The data set contains more than 10,000 tweets that were hand classified. 
Link to dataset: https://www.kaggle.com/c/nlp-getting-started/overview

For this project, I applied important parts of a modeling scheme: exploratory data analysis, 
data cleaning, feature extraction, model fitting, and performance assessment.

Results and code are reported in the Jupyter notebook saved in this repository. 

In short, we fit the data to a recurrent neural network (LSTM) which yielded the best results: auc of 0.87.

