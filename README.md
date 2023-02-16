# Sentiment analysis on IMDB Movie Reviews with Pytorch

A project, Using ROBERTA model with pytorch for sentiment analysis task on IMDB movie reviews.

<img title="" src="https://github.com/rojinakashefi/IMDBMovie-SentimentAnalysis/blob/main/images/loss-per-epoch.png" alt="" width="316" data-align="center">

<img title="" src="https://github.com/rojinakashefi/IMDBMovie-SentimentAnalysis/blob/main/images/output.png" alt="" width="314" data-align="center">

## Description

1. Pre-processing step includes: stemming, stop words and punctuation removal.

2. Data analysis step includes:  seaborn library to analysis and visualize the data.

3. Customized our dataset using pytorch Datast library and used Dataloader for creating our batches of data.

4. Trained using pretrained Roberta model class.
   
   <img title="" src="https://github.com/rojinakashefi/IMDBMovie-SentimentAnalysis/blob/main/images/The-RoBERTa.png" alt="" width="338" data-align="center">

5. Implement Validation and plotted Confusion matrix. The other evaluation criteria are shown as well.
   
   <img title="" src="https://github.com/rojinakashefi/IMDBMovie-SentimentAnalysis/blob/main/images/confuison.png" alt="" width="246" data-align="center">

## Project layout

- Load the Training data
- Data pre-processing and Data cleanning
- Exploratory data analysis
- Dataloader
- Model Creation
- Model Training
- Loss Function and Optimizer
- Save Model
- Model validation

## Dataset

https://www.cs.cornell.edu/people/pabo/movie-review-data/

## Libarary used

Sklearn, Transformers, PyTorch, Seaborn, NLTK


