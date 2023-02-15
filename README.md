# Wrangling-Analyzing_WeRateDogs_Twitter_Data

#### Introdauction

##### Data
The WeRateDogs Twitter archive contains basic data for 5000+ tweets, of which, some of the tweets are retweets and do not contain dog ratings and images. This exploration considers only original tweets with ratings that have images. The image data is gathered via url using Request library. 
The dog rating uses a unique system, [unique rating system](http://knowyourmeme.com/memes/theyre-good-dogs-brent), where the rating numerators are greater than the denominators. Tweets upto August 1, 2017 will be gathered and cleaned.
The requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in the dataset.

The goal of the project is to gather, wrangle, and analyze the data with focus on the accuracy with which the algorithm predicts dog images. 
The algorithm attempted three predictions notated as p1, p2, and p3 in the gathered data. These predictions produced outcomes notated as p1_dog, p2_dog, and p3_dog which signifies the image(s) identifies by the algorithm in that attempt. The prediction is perform at certain confidence level for each attempt and is notated as p1_conf, p2_conf, and p3_conf for first, second, and third prediction respectively.
