TEXT MINING AND SENTIMENTAL ANALYSIS IN MCDONALDS TEXAS STORES.

The project aims to find out which restaurant in the state of Texas has the highest number of very bad reviews. Furthermore, it aims to create a model that can detect the sentiment of new reviews



Libraries are loaded and data regarding the store address of the restaurant is visualized.

PART ONE DATA PREPROCESSING

A dataset including only Texas stores is created and visualized by the store addresses.

Sentiment analysis is used to get the sentiment of the reviews for the texas stores, most of reviews are positive.

Percentage of very bad reviews is calculated over the total number of reviews finding that 8500 US-290, Austin, TX 78724, United States has 	19.438445% of very bad reviwes.


PART 2 TEXT MINING MODEL TRAINING AND EVALUATION.

text mining is used to prepare the  text data to be visualized.

Visualization show the most occuring words in the restaurant located on 8500 US-290, Austin, TX 78724, United States 

Note that the code used in this visualization generate an error if used in python, use the same file in google collab to avoi the error.

Next sentiment column is generated to divide reviews in positive negative and neutral.

CountVectorizer is employied to encode the text .
Data is split between X containing the reviews and y contaiong the sentiment subsequently X and y are split between  test and train, SMOTE is used to balance the label variable(sentiment).

Random Forest Classifier is trained and fitted to predict the sentiment of new reviews.

The model is evaluated giving an accuracy of 0.89
