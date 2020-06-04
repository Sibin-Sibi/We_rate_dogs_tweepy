# WeRateDogs Data Wrangling Project

####  Introduction

This project is a data wrangling project, which mainly focus on fixing the data quality and tidiness issues using python. The dataset used is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. And the numerators almost always greater than 10, because "they're good dogs Brent." The tweet archive records using in this project contains basic tweet data (tweet ID, timestamp, text, etc.) for all 2356 of their tweets as they stood on August 1, 2017. 

This project includes steps as follows:
- Data wrangling, which consists of: gathering data, assessing data, and cleaning data 
- Storing, analyzing, and visualizing your wrangled data.

Data collected is stored in folder **data**, which have:
1. `twitter_archive`: The WeRateDogs Twitter archive, which is provides by the Udacity Course and I use pd.read_csv() to import them into dataframe.
2. `image_predictions`: The tweet image predictions, i.e., what breed of dog (or other objects, animal, etc.) is present in each tweet according to a neural network. This file ('image_predictions.tsv') is hosted on Udacity's servers and downloaded programmatically using the requests library and the provided url.
3. `tweet_json`: Using the tweet IDs in the WeRateDogs Twitter archive, query the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called 'tweet_json.txt' file. Each tweet's JSON data is written to its own line.

Steps for data wrangling is provided in **wrangle_report.pdf** file.


The final insights generated of the project is provided in **act_report.pdf**, we have used matplotlib and seaborn to perform exploratory data analysis. 
