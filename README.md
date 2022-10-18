# Twitter Dataset column breakdown
1)Created at
This attribute will include data values which have date and time at which a particular tweet has been posted.There are no missing values in this column.
Datatype: String

2)ID
This attribute will include data values which have ID’s of twitter users who have posted the tweet.There are no missing values in this column.


3)Lng (Longitude) & Lat(Latitude)
These attributes will give the longitude and latitude coordinates which will be used to know the geographical location of the user at which the tweet has been posted.Having Geographical location is pivotal.Since many users don’t enable this feature in twitter.We have some missing values in our dataset.We have to deal with the missing values during data preprocessing.There are 114792 missing values in both the columns.
Datatype: Float
Type: 

4)Topic
This attribute will include a collection of keywords posted by users in twitter regarding climate change issues like:
#Weather Extremes 
#Importance of Human Intervention 
#Seriousness of Gas Emissions
#Ideological Positions on Global Warming
#Weather Extremes
#Impact of Resource Overconsumption
#Donald Trump versus Science
#Global stance
#Politics
#Seriousness of Gas Emissions
#Significance of Pollution Awareness Events

Also , there are some undefined or unrelated one word hashtags , which can be dropped during preprocessing.

Datatype: String
Type: Categorical

5)Sentiment
This attribute generally refers to the user's attitude towards  climate change i.e Positive ,negative or neutral.The scale ranges from -1 to 1. 1 being positive ,-1 being negative and 0 being a neutral reaction. 

Datatype: Float
Type: Categorical


7)Stance
This attribute refers to the stance of the tweet posted by twitter user.This generally includes three data values believer, denier and neutral.If tweet supports the man-made climate change (believer) , if tweet does not believe in the man-made climate change(denier) and if tweet does neither support nor deny about climate change (neutral)

Datatype: String
Type: Categorical

8)Gender
This attribute refers to the gender of the user who has posted the tweet i.e Male and female.This column can refer to attitude of particular gender towards climate change.There are some undefined data values in the Gender column which  need to be handled during preprocessing.

Datatype: String
Type: Categorical

9)Temperature_average
This attribute refers to the Average temperature at the location of the user using longitude and latitude coordinates where the tweet has been posted.There are missing values in this particular column which we need to handle during data preprocessing.This column has 114792 missing values.

Datatype: Float
Type: Numerical

10)Aggressiveness
This attribute measures the text aggression of the tweet posted by the user.This includes two data values Aggressive or not aggressive.This column has 1 missing value 

Datatype: String
Type: Categorical

#cmpe255_group_gapv
