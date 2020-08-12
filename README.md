# Detecting-Sarcasam-on-Reddit
### Executive Summary
Data Collected from: https://www.kaggle.com/danofer/sarcasm
The aim of this project is to detect sarcastic remarks from Reddit posts on numerous Reddit pages based on the content of the comment as well as other variable such as to number of upvotes, downvotes and original post(parent post) from which the comment was collected has an impact on detecting sarcasm,Furthermore the aim of this project is to create a model which can be repurposed and used in a variety of projects.
<br><br>

### Pre-Processing Steps
- Explanatory Data Analysis of each feature column.
- Analysing which columns contribute to the label most
- Inspecting the different subreddits
- Checking distrubtion of labels 
- Feature extraction using tfidf which converts a collection of documents to a matrix of TF-IDF features
<br><br>
### Statistical Anaylsis
- ensured that the labels were equally distributed 
- inspected the distribution of Subreddits

<br><br>
### Questions:
- Q1. Which feature contributes most to our label?
- Q2. which type of model is best able to predict sarcasam from the dataset

<br><br>
### Methodology
1. **Business Understanding** 
- The aim is to create a model to detect sarcasam from reddit posts, another aim is to use the model framework made from this project for outside applications in things like online shops reviews, any reviews/critique websites, forums that disucss items and much more. Therefore this model will have much more flexibility and use and can be used as a 3rd party application for the specific business needs of the customers
<br> <br>
2. **Data Understanding**  
Column Names and descriptions for Data set:
- label: 1 indicating it was a sarcastic comment and 0 for a non-sarcastic comment
- comment: the textual comment
- author: which user posted that comment
- subreddit: the subreddit that the comment was posted to(subreddit is similar to the theme/genre)
- score: the score given when aggregating the ups and downs.
- ups: the number of upvotes a comment received
- downs: the number of downvotes a comment receieved
- date: data a comment was posted
- created_utc
- parent_comment: the original post/comment from which the comment is a child of.

<br><br>
3. **Modelling**
- Baseline model using Logisitic Regression, which was further improved by applying a grid search to find the best hyper parameters. 
- RandomForest with GridSearch. 
- (WIP)GradientBoost 
- (WIP)Neural Network 

<br><br>
4. **Findings**
- Final Logistic Regression results: 
 CV score = 0.721
 Accuracy Score: 0.72 
 Recall Score: 0.68 
 F1-Score: 0.71


<br><br>
5.  **Future Tasks**


