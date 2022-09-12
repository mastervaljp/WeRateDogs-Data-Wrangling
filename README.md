# WeRateDogs-Data-Wrangling

## Data Wrangling Report

### 1.0.1 Project Description
WeRateDogs is a twitter account that rates people dogs with humorous comment about the dog
by sharing the dog’s image and brief comments about it. These ratings almost always have a
denominator of 10. The numerators though? Almost greater than 10. 11/10, 12/10,13/10 etc.
Why? Because "they’re good dogs Brent".
WeRateDogs has over 4 million followers and has received international media coverage. They
have shared 5000+ of their tweets containing some basic data such as there breeds and brief
comments.

---------------------------------
### 1.0.2 Project Objective
The objective of this project is to gather these data from different sources, thoroughly assess them
and clean them to raise the tidiness and quality of the data in order to create a correct analysis.

-------------
### 1.0.3 Data Gathering
The data used for this analysis was gathered from three different sources
1. twitter_archive_enhanced.csv WeRateDogs twitter archive file, which was downloaded
manually.
2. image_predictions.txt an image prediction file downloaded programmatically from its Url
using request library.
3. twitter This last data was generated from Twitter API using Tweepy library as
tweet_json.txt.
