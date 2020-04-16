# Coronavirus-Public-Arabic-Twitter-Data-Set


The repository contains a collection of Arabic Tweet IDs associated with the novel coronavirus COVID-19. The dataset contains data collected from December 1st 2019 until April 11th 2020. We used Crimson Hexagon a social media analytic platform that provides paid data stream access. To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), we are only publicly releasing the Tweet IDs of the collected Tweets. The data is released for non-commercial research use. The total number of tweets collected until now is 3,800,855.

The associated paper to this repository can be found here: [Coronavirus: Public Arabic Twitter Dataset](https://www.preprints.org/manuscript/202004.0263/v1)



# Data Organization

The Tweet-IDs are organized as follows:

- TweetIDs files are organised in folders indicating the year and month of the collection.
- Indivisual Tweet-ID files contains a collection of Tweet IDs, all follow the same structure. 
- Each file is prefixed with "coronavirus-tweet-id-" followed by YEAR-Month-DAY.


# Dataset Discerption 

- The main focus in the data set collected was on hashtags used in Saudi Arabia, although they might be used in Arabic-speaking countries outside of Saudi Arabia.  
- The folder keywords contains the list of keywords used for all of the topic.
- The file accounts.txt contains the Saudi Arabia ministry of health accounts, with a total of 1600 tweets populated by these accounts.

| Hashtags Topics  | Number of tweets |
|  :---: |  :---: |
| Populated by Saudi governmental accounts  | 1,313,055  |
| Discussing Precautionary measures applied by governments  | 492,343 |
| Showing social solidarity | 219,768 |
| Supporting decisions taken by governments  | 1,814,477 |


## Dataset Summary Statistics 
| Number of original tweets  | 707,829 |
|  :---: |  :---: |
| Number of retweets  | 3,093,026 |
| number of unique users  | 1,000,244 |
| number of unique users who wrote original tweets  | 323,876 |


# Data Retrieval 

You can use tools such as the [Hydrator](https://github.com/DocNow/hydrator) and [Twarc](https://github.com/DocNow/twarc) to retrieve the tweets. keep in mind that some of these tweets might be removed.


# Data Usage Agreement

This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), and cite the following manuscript:

Addawood, A. Coronavirus: Public Arabic Twitter Dataset. Preprints 2020, 2020040263 (doi: 10.20944/preprints202004.0263.v1).


# Contat Information

if you have any questions or suggestions regarding the dataset please contact **Dr.Aseel Addawood** at **aasdawood[at]imamu[dot]edu[dot]sa**
