# Basic Sentiment Analysis Project Using Bag of Words and Negation

### 

## Introduction

#### The goal of this project is to perform sentiment analysis on a dataset of reviews using Python. In order to achieve this, we first perform necessary data cleaning on the reviews of clothing shop dataset. This includes removing irrelevant information and pre-processing the text.In my sentiment analysis project, I employed a machine learning-based approach where I trained algorithms using pre-labeled texts dataset. These algorithms were then utilized to predict the sentiment of new and unseen texts. This approach is more precise than the rule-based approach as it can understand the context of the text and learn from the data. However, it necessitates a significant amount of labeled data for training and may be computationally demanding.

## Data Cleaning

#### When cleaning the data for sentiment analysis, it is important to avoid removing stop words, as they may carry some contextual meaning. Similarly, converting everything to lowercase may result in the loss of important emotional context conveyed by capital words. Therefore, we need to carefully preprocess the text while preserving the relevant information.

## Feature Engineering

#### After cleaning the data, we used the sentence_polarity corpus to train our model. We generated featuresets using Bag-of-Words (BOW) and Negation words. We combined these two feature sets to form a single feature set.

## Model Training

#### Finally, we trained the model using Naive Bayes theorem and evaluated its accuracy. The model resulted in an accuracy of 77.7%.

## Conclusion

#### In conclusion, this project shows that sentiment analysis can be performed on reviews dataset using Python. We have demonstrated the importance of data cleaning and feature engineering for this task. Furthermore, we have shown that the Naive Bayes algorithm can be an effective tool for sentiment analysis.
#### During the sentiment analysis process, we discovered that a single text may consist of multiple sentences and may not necessarily indicate a single sentiment. For instance, we came across a review text with two positive sentences and one negative sentence. Therefore, it is crucial to consider this aspect while performing sentiment analysis. If the positive sentences outweigh the negative ones, we can consider the text to be positive based on rule-based analysis, and this would be a hybrid approach to sentiment analysis. Additionally, some texts may be comparative or may discuss a specific aspect, and we need to analyze them more carefully. In contrast, for a simple assertive sentence, we can perform basic sentiment analysis and assign a positive, negative, or neutral tag, which is the easiest and most basic form of sentiment analysis.
