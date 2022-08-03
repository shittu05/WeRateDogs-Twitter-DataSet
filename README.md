# WeRateDogs-Twitter-DataSet
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

The wrangling process was carried out in 3 stages:
- Gathering of data
- Assessing data
- Cleaning data

### GATHERING DATA
The data used for wrangling processes were gathered from 3 different sources
- Enhanced Twitter Archive: This data was downloaded manually
- Image Prediction tsv File: The data for this file was downloaded programmatically by importing requesting library
- tweet_json.text: Additional data file was downloaded from Twitter by using the tweepy library to query additional data via the Twitter API. the resulting data
generated was a JSON, which was later stored in a text file

### ASSESSING DATA
After gathering from 3 different sources, each data was assessed visually with code editors, and spreadsheets. Furthermore, after assessing the data visually, the data
was programmatically assessed using the panda's inbuilt functions like head, tail,info, sample, and describe to gain more insights into the data. 8 different quality
issues were highlighted and 2 tidiness issues were highlighted after assessing the
data visually and programmatically.

### CLEANING DATA
The highlighted quality and tidiness issues that were documented during the assessing stage were thoroughly cleaned during this phase. Before cleaning the data a copy of all the data to be cleaned was generated first.

## ANALYSIS AND VISUALIZATION
- Linear correlation was noted to exist between retweet count and favorite count for dog types
- In Dog categories pupper has the highest number in terms of value counts  favotite while floofer has the lowest
- Charlie, oliver, Cooper and lucy are noted to be the most popular dog names in the dataset
