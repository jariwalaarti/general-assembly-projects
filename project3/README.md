# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & Classification



## Problem Statement

In this project we would like to get more insights in the similarities and differences between two of the most competitive online streaming platforms - Netflix and Disney plus. First we will classify the posts from these two subreddits and then carry out analysis that would help understand users which platform is more suitable for them and hence which one they would like to choose.

### Executive Summary

Netflix is an American, subscription-based service offering online streaming from a library of films and television series, including those produced in-house. Similar to Netflix, Disney Plus service distributes films and television series produced by The Walt Disney Studios and Walt Disney Television and is one of the biggest competitor of Netflix.

Due to Covid, there has been a tremendous increase in usage of OTT platforms as cinemas were shut down and more people were staying home.

As more people are shifting towards OTT platform, we would like to get more insights in the similarities and differences between Netflix and Disney Plus. This analysis would help understand users which platform they would prefer based on the discussion of the subreddit posts and decide which one they would like to choose.

The following process has been carried out for classifying and analyze the posts from the subreddits.

**Web Scraping:**

Two subreddits namely, Netflix and Disney Plus have been scraped to retrieve sufficient posts for our analysis.

**Data Cleaning:**

For this analysis we just need text data, hence have removed several meta data that comes with the scraped posts.

**Data Preprocessing**

In order to carry out meaningful analysis, the text data have been preprocessed to remove html tags, tokenized and lemmatized.

**Exploratory Visualization:**

Exploring the maximum occurring words for both the subreddit posts and also analyze the common words through graphs.

**Data Modeling**

Create few classification models using Logistic Regression, Naive Bayes and Random forest and compare the accuracy to and decide on the best model.

**Conclusion & Recommendation**

Based on models and feature importance, provide evaluation and recommendations to users.

### Dataset

Posts data for Netflix and Disney Plus subreddits have been scraped from [Reddit](https://www.reddit.com/)

The entire process has been carried out in the following notebooks:

Scraping Netflix : Scrape posts for Netflix subreddit

Scraping DisneyPlus : Scrape posts for Disney Pus subreddit

Cleaning And Exploratory Analysis - Clean and preprocess the data and analyze using visualizations

Modelling - Creating and evaluating models, predict and conclude.


### Conclusion & Recommendation:

**Conclusion**

We compared several models through their accuracy scores with and without additional stopwords added. The score was much better without the additional stopwords, but the later would give us more ethical predictions and would not be too biased. So the final model chosen was Naive Bayes with Count Vectorizer which returned an accuracy score of 77% for test data.

Now from the analysis we can say that there are several obvious common words between netflix and disney plus like watch, series, tv, season, like, recommend, movi, stream, finish and so on. From these words we can interpret that people in general are talking about watching/recommending or have finish watching a series or a movie on a streaming platform.

In addition to these, other common words like access, subscript, contri, etc would depict that they are also talking or inquiring about the subscription or access policies in different countries.

We can also derive from the analysis that people on the subreddit posts are talking about varied genres like crime, marvel, drama, war, love, documentri, anime.

Aside from the common words unique words like wandavision, stranger things, raya, drama, war, marvel etc which are specific to one platform also came up in the top 30 features that were important in predicting the posts. Here we can get a clear understanding of which words belong to which platform. <br>
Examples:
- Wanda vision is the new series aired in January 2021 on Disney plus.
- Stranger things is the American series on Netflix since 2016.
- Now if we consider drama and marvel features, we can clearly say that Disney plus airs most of the marvel movies and netflix airs most of the drama movies/series.


From the exploratory analysis and feature importance, we can say that fewer movies or series name were highlighted. The reason behind this might be that the new series/movies are aired all the time on both the platforms, and so it seldom occurs that the same movie or series is mentioned several times to come up in the top discussed words which is expected. However, w egot better insights of movie names from Disney plus posts as compared to Netflix posts. Maybe can dig out more features by adding more stop words in future analysis.

**Recommendations:**

- Disney plus contains movies like Wanda vision which is a superhero fiction movie. It also contains few anime movies like Raya the last dragon, the Simpsons, etc. Hence based on the above and external analysis, on genres basis we can suggest users to go for Disney plus if they are more interested in marvel, animated movies or series.
- Fewer named of movies and series came up in our analysis but features like drama, stranger things (series on Netflix), documentary, anime etc. suggest that if users are more inclined towards these genres should go for Netflix.
