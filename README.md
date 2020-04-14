# Coronavirus-Public-Arabic-Twitter-Data-Set


The repostory contains a collection of Arabic Tweet IDs associated with the novel coronavirus COVID-19. The dataset contains data collected from Janueary 1st 2020. We used Crimson Hexagon a social media analytic platform that provides paid data stream access. To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), we are only publicly releasing the Tweet IDs of the collected Tweets. The data is released for non-commercial research use. The total number of tweets collected until now is 3,800,855.


# Data Organization

The Tweet-IDs are organized as follows:

- TweetIDs files are orgnized in folders indicating the differnt types of hasgtahg topics - explained below.
- Indivusal topic files contains a collection of files for hastags realted to that topic.
- Each file is prefixed with "coronavirus-tweet-id-HASHTAG NAME".


# Dataset Discrption 

- The main focus in the data set collected was on hashtags used in Saudi Arabia, although they might be used in Arabic-speaking countries outside of Saudi Arabia.  
- The folder keywords contains the list of keywords used for each topic.
- The file accounts.txt contains the Saudi Arabia ministry of health accounts, with a total of 1600 tweets populated by these accounts.

| Hashtags Topics  | Number of tweets |
|  :---: |  :---: |
| Populated by saudi governmental accounts  | 1,313,055  |
| Discussing Precautionary measures applied by governments  | 492,343 |
| Showing social solidarity | 219,768 |
| Supporting decisions taken by governments  | 1,814,477 |


## Dataset summary statistics 
| Number of original tweets  | 707,829 |
|  :---: |  :---: |
| Number of retweets  | 3,093,026 |
| number of unique users  | 1,000,244 |
| number of unique users who wrote original tweets  | 323,876 |


# Data retrival 

You can use tools such as the [Hydrator](https://github.com/DocNow/hydrator) and [Twarc](https://github.com/DocNow/twarc) to retrive the tweets. keep in mind that some of these tweets might be removed.


# Data Usage Agreement

This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), and cite the following manuscript:



# Contat Information

if you have any questions or suggestions regarding the dataset please contact **Dr.Aseel Addawood** at **aasdawood[at]imamu[dot]edu[dot]sa**
