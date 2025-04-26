 Name: twitter_disaster.csv

Features:
id: Unique identifier for each tweet
text: The actual content of the tweet
location, keyword: Metadata about the tweet
target: 1 if the tweet refers to a real disaster, 0 otherwise.


Project Steps:
Import Libraries
Pandas, NumPy, Matplotlib, Seaborn, NLTK, Regex
Data Cleaning
Filled missing values in keyword with mode
Replaced missing location values with "Unknown"


Exploratory Data Analysis (EDA)
Class distribution analysis (real vs non-disaster tweets)
Keyword frequency visualization
Analysis of user mentions, hashtags, and tweet lengths


Feature Engineering
Extracted user mentions and hashtags
Created new features like has_hashtags


Visualizations
Pie charts, bar plots, and histograms to understand the data distribution.


Requirements-- pandas matplotlib seaborn nltk wordcloud.

Author
Name: Upasna AGrawal
