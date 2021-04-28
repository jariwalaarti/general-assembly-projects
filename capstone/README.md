# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Capstone Project : Jigsaw Unintended Bias in Toxicity Classification



## Problem Statement

The objective is to build a model that is capable of detecting the toxic comments over the internet. The comment can be a threat, insult, rude. Moreover, model should also be able to detect the unintended bias in the comments and not associate them as toxic comment.

In addition to this we would also like to get insights on which are the topics which ignites this hateful reaction over the internet platforms.

## Executive Summary

Over the past few years online conversations over social media, communities have become very influential and is turning out to be negative. People have different opinions and they sometimes tend to express it as an insult/threat. Due to this reason several platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

The Conversation AI team, a research initiative founded by Jigsaw and Google, builds technology to protect voices in conversation. A main area of focus is machine learning models that can identify toxicity in online conversations. Previously when the models were build to recognize toxicity in the comments they found that the models incorrectly learned to associate the names of frequently attacked identities with toxicity. Models predicted the comments which includes the mention of such identities(gay, homosexual, asian, black, white, etc) as toxic even though they are not. <br> 
Example: "I am gay"
This happens because these identities are referred in offensive ways. Hence Conversation AI team held a challenge on Kaggle named Jigsaw Unintended Bias in Toxicity Classification.

In this project we will build a model that detects the toxic comments, keeping in mind the unintended identity bias. We will also analyze and extract the topics that receive the toxic response on internet.

This will assist online communities to remove such toxic comments and help online discussion become more productive in future.

## Dataset

The dataset has been adapted from [Kaggle](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification).

|Type|Fields|Description|
|---|---|---|
|Feature|Comment Text|The text of the comments acquired from over the internet. <br>This is the field that will be used for prediction.|
|Target|Toxicity|The toxicity comtains the probability of a comment being toxic or not. <br>If the value is >= 0.5 the comment is toxic else non toxic.|
|Toxicity Subgroups|-Severe Toxic<br> -Obscene <br> -Identity Attack <br> -Insult <br> -Threat <br> |These are additional toxcity subtype attributes provided for analysis purpose only. <br>We do not need to predict them. They are also provided in form of probabilities.|

## Process

The entire process of analysing and modelling has been carried out in 4 notebooks:

1 Clean Data & EDA  - This notebook contains the cleaning for train and test data. It also includes visual exploratory analysis for train data.

2 Topic Modelling - This notebook contains analyzing and extracting the topics for toxic comments.

3 Basic Models - This notebook contains the basic models and their evaluation.

4 BERT Model - This notebook contains the training and evaluation of bert model. This is where an overall comparison among the basic models and bert models have been done and conclusions and recommendations are provided.

### Conclusion & Recommendation:

**Conclusion:**

We were able to build a model using **BERT** that can detect identity biased toxicity in the comments over the internet with test <br> **Accuracy : 95%** and **Recall : 64%**.

**Recommendation:**

Most online communities have some rules and regulations for commenting. For some platforms, moderators delete offensive comments or even close the article/post because of the destructive conversations. 

This model would help the online platforms to regulate the insults, threats and toxic comments by identifying and deleting them or not allowing to post such comment. This will help the future conversations to be more productive and positive.