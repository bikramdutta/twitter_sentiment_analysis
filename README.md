# Twitter Sentiment Analysis
*Analytics Vidhya Datahack Competition*

## Project Overview
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

## Motivation
Hate  speech  is  an  unfortunately  common  occurrence  on  the  Internet.  Often social media sites like Facebook and Twitter face the problem of identifying and censoring  problematic  posts  while weighing the right to freedom of speech. The  importance  of  detecting  and  moderating hate  speech  is  evident  from  the  strong  connection between hate speech and actual hate crimes. Early identification of users promoting  hate  speech  could  enable  outreach  programs that attempt to prevent an escalation from speech to action. Sites such as Twitter and Facebook have been seeking  to  actively  combat  hate  speech. In spite of these reasons, NLP research on hate speech has been very limited, primarily due to the lack of a general definition of hate speech, an analysis of its demographic influences, and an investigation of the most effective features.

## Analytics Vidhya Competition Details
url: https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/#ProblemStatement


## Data
Our overall collection of tweets was split in the ratio of 65:35 into training and testing data. Out of the testing data, 30% is public and the rest is private.

## Data Files
train.csv - For training the models, we provide a labelled dataset of 31,962 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.
There is 1 test file (public)
test_tweets.csv - The test data file contains only tweet ids and the tweet text with each tweet in a new line.


## Software and Libraries

This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE or any other program which lets you edit .ipynb files.
It is highly recommended  that you use the Anaconda distribution to install Python, since the distribution includes all necessary Python libraries
as well as Jupyter Notebooks.
It is recommended that you use Google Colab for implementing the BERT model as it provides free GPU, which is essential for accelerating the training process.

The following libraries are expected to be used in this project:

* NumPy
* pandas
* Sklearn / scikit-learn
* Matplotlib (for data visualization)
* Seaborn (for data visualization)
* Bert
* Tensorflow, Keras
* tensorflow_hub
* Keras: Layers :: Input, Dropout, GlobalAveragePooling1D
* Keras: Modesl :: Model, Sequential
* Keras : Callbacks :: ModelCheckpoint, EarlyStopping, Callback
* tokenization
* wordcloud.STOPWORDS
* collections.defaultdict
* GridSearchCV
* cross_val_score
* TfidfVectorizer
* CountVectorizer
* time
* re
* KNeighborsClassifier
* RandomForestClassifier
* SVC
* confusion_matrix
* accuracy_score
* train_test_split


## How the project is organized

There are 2 Jupyter Notebooks that are supposed to be ran in order

1. tweetClassification.ipynb
2. tweetClassification2.ipynb

The notebooks expect that the following files are present in the `data` folder:
1. train.csv
2. test.csv
3. sample_submission.csv

**The data is the provided by Kaggle, as the problem statement is a part of a Kaggle Competition**

## Additional data required by the project
1. Glove Embeddings: https://www.kaggle.com/authman/pickled-glove840b300d-for-10sec-loading
2. FastText Embeddings: https://www.kaggle.com/authman/pickled-crawl-300d-2m

