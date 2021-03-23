# Sentiment-Analysis-of-U.S-Presidential-Elections-2020
Topic Modelling was done using NMF and LDA on more than 1000 news articles published by major news outlets to identify the important issues that were influencing the election. Polarity forecasting was done using prophet model. Sentiment analysis of twitter data was done using LSTM and TextBlob to identify possible democratic and republican strong hold states and Text Classification and artificial tweets generation was done using Multinomial Naive Bayes and Markov Chain models using Trump and Bidens official twitter data.


Each ipynb file contains the code for a specific task.

FInal_602_media_bias.ipynb:- Contains the code for topic modelling, sentiment analysis of more than 1000 news articles that were published during the election months from major news outlets like CNN, FOX, NBC, CBS.

Final_keywords_lsltm.ipynb:- Contains the code of sentiment analysis of twitter data that was gathered based on election specific neutral keywords. Based on the location tag of the tweet the tweets are grouped into states and by analyzing the polarity of those tweets towards the candidates democratic and republican stronghold states are identified.

final_candidate_twitter_analysis.ipynb:- Contains the code where we analyze both the presidential candidates twitter accounts to determine the reach and activity of the candiadtes.
