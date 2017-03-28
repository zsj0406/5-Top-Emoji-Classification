# 5-Top-Emoji-Classification
The aim of this project is to build a classification model for 5 top popular emojis.

We used the dataset of Spanish English Bilingual Youth Texts from https://byts.commons.gc.cuny.edu/. 

Steps:
- Connect to MySQL server to load the data
- Calculate the top 5 frequency emojis from text messages
- Pre-porcess text messages, retrieve all text messages that including top 5 emojis and delete all emojis from these messages, provide labels for all test messages
- Build train and test dataset
- Use Naive Bayes and Logistic regression models to classfy text messages
