# **Play-Store-App-Review-Analysis**

# **INTRODUCTION**

In today’s scenario we can see that mobile apps
playing an important role in any individual’s life. In
today’s era, the Google Play Store is the largest
and most popular android app store. It is flooded
with millions of applications and it provides wide
collection of data on features like ratings, price and
number of downloads and apps description. Many
apps are being developed as apps are easy to
create and its lucrative. But its important for
developers to know which apps are loved by
customers and are trending in market so that he
develop only those apps and also there is a high
competition between app providers producing
similar applications. Analyzing customer needs is
one of the bizarre tasks in the business world
today. Hence proposing analyze data to developer
that what customer is likely to download, which
category got the maximum downloads this all plays
a crucial role in app development. With enormous
challenge from everywhere throughout the globe,
it is important for a designer to realize that he/she
is continuing in the right way or not. To hold this
income and their place in the market the
application designers may need to figure out how
to stick into their present position. The dataset with
10k Play Store applications is available to analyze
the market of android. It can be examined to
analysis the different category such as family,
communication, entertainment, tools, music,
camera etc.

# **PROBLEM STATEMENTS**

1). Which apps are the highest earners?

2). Top categories on Google Playstore?

3). Ratio between paid and free apps

4) Distribution of apps based on its size

5) Apps with the highest number of positive reviews

6) Apps with the highest number of negative reviews.

7) Is sentiment_subjectivity proportional to sentiment_polarity?

8) Does Last Update date has an effects on rating?

# **WHAT IS EXPLORATORY DATA ANALYSIS?**

Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets for patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset and summarize their main characteristics, often employing data visualization methods. It is an important step in any Data Analysis or Data Science project. It helps determine how best to manipulate data sources to get the answers you need.

EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better and make it more attractive and appealing.

The following are the various steps involved in the EDA process:

Problem Statement - We shall brainstorm and understand the given data set. We shall study the attributes present in it and try to do a philosophical analysis about their meaning and importance for this problem.

Hypothesis - Upon studying the attributes present in the data base, we shall develop some basic hypothesis on which we can work and play with the data to look for the varied results which we can get out of it.

Univariate Analysis - It is the simplest form of analyzing the data. In this we would initially pick up a single attribute and study it in and out. It doesn't deal with any sort of co-relation and it's major purpose is to describe. It takes data, summarizes that data and finds patterns in the data.

Bivariate Analysis - This analysis is related to cause and the relationship between the two attributes. We will try to understand the dependency of attributes on each other.

Multivariate Analysis - This is done when more than two variables have to be analyzed simultaneously.

Data Cleaning - We shall clean the dataset and handle the missing data, outliers and categorical variables.

Testing Hypothesis - We shall check if our data meets the assumptions required by most of the multivariate techniques.


# **ANALYSIS SUMMARY** 

In this project of analyzing play store applications, we have worked on several parameters which would help AlmaBetter to do well in launching their apps on the play store.

In the initial phase, we focused more on the problem statements and data cleaning, in order to ensure that we give them the best results out of our analysis.

Developing apps related to the least categories as they are not explored much. Like events and beauty.
Most of the apps are Free, so focusing on free app is more important. Focusing more on content available for Everyone will increase the chances of getting the highest installs.
They need to focus on updating their apps regularly, so that it will attract more users.
They need to keep in mind that the sentiments of the user keep varying as they keep using the app, so they should focus more on users needs and features.

# **CONCLUSION**
Reading the dataset and comprehending the problem statement. Our major challenge was data cleaning.

Handling the error, duplicate and NaN values in the dataset.

13.60% of reviews were NaN values, and even after merging both the dataframes, we could not infer much in order to fill them. Thus we had to drop them. This is just 10% of the cleaned data, we could have given more valuable analysis, if we had atleast 70% - 80% of the data available in the merged dataframes.

User Reviews had 42% of NaN values, which could have been used for developing an understanding of the category wise sentiments, which would help us to fill 13.60% NaN values of the Reviews column.

There is so much more which can be explored. Like we have current version, android version available which can be explored in detail and we can come out with more analysis where we can tell how does these things effect and needs to be kept in mind while developing app for the users.

Designing multiple visualizations to summarize the information in the dataset and successfully communicate the results and trends to the reader.

# **REFERENCES**

GeeksforGeeks Analytics Vidhya Stackoverflow Towards data science Python libraries documentation Data camp



