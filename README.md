# WeRateDogs-Twitter-Archive-Data-Wrangling
## Overview
The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, commonly known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs and includes a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc.
## Context
My goal is to investigate and wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

## Steps Taken In Analysing The Datasets
> #### Data Gathering: 
Three datasets were given to perfom this wrangling. These datasets are
- twitter_archive_enhanced.csv
- image_predictions.tsv
- twitter API
> #### Data Accessing: 
There are 2 ways in which data can be accessed. They are:
- Visual Accessment
- Programmatic Accessment
In this stage, I identified some data quality and tidiness issues.
> #### Data Cleaning
Firstly, I made a copy of each datasets. After merging and cleaning my dataset, I also made a copy of my merged dataset.
> #### Storing Cleaned Data
After cleaning my data, I stored my data in a csv file which was later used for exploratory data analysis.
> #### Exploratory Data Analysis


> #### Conclusions
- Twitter for Iphone is the most popular tweet source.
- The golden retriever breed is the most popular dog breed while irish_wolfhoundis the leave popular dog breed among others.
- There is a positive correlation between favorite_counts and retweets.
- Charlie, cooper, oliver are the most common names.
- Soft-coated_wheaten_terrier is the breed with highest average rating.
- Standard_poodle is the top average retweeted dog breed while groenendael is the least average retweeted dog breed.
- Bedlington_terrier is the breeds with the highest average favorite_counts.
- Pupper is the most common dog stage.

## Tools
- Jupyter Notebook
- Python Libraries: Pandas, Tweepy, Requests, Matplotlib


