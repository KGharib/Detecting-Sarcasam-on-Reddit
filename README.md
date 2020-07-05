# Detecting-Sarcasam-on-Reddit
### Executive Summary
Data Collected from: https://www.kaggle.com/danofer/sarcasm
The aim of this project is to detect sarcastic remarks from Reddit posts on numerous Reddit pages based on the content of the comment as well as other variable such as to number of upvotes, downvotes and original post(mother post) from which the comment was collected has an impact on detecting sarcasm 
<br><br>


<br><br>
### Pre-Processing Steps
- Explanatory Data Analysis of each column and checking the distribution
- finding which columns contribute to the label most
- Inspecting the different subreddits
- Checking distrubtion of labels 
<br><br>
### Statistical Anaylsis

<br><br>
### Questions:
- Q1. Which variable contributes most to our label?
- Q2. which model is able to best predict sarcasam from the dataset

<br><br>
### Methodology
1. **Business Understanding** 
- We want to create a model to detect sarcasam from reddit posts in order to use the model for outside applications in things like online shops, websites that give reviews, forums that disucss items and much more. Therefore we are building this model so that it can be used as a 3rd party application for the specific business needs of our customers
<br> <br>
2. **Data Understanding**  
Column Names and descriptions for Data set:
label
comment
author
subreddit
score
ups
downs
date
created_utc
parent_comment

<br><br>
3. **Modelling**
Baseline model is Logistic Regression
optimized logistic regression through gridsearch
used RandomForest with gridsearch to improve results
applied GradientBoost to further improve results
Finally applied Neural network to get the best results

<br><br>
4. **Findings**

<br><br>
5.  **Future Tasks**


