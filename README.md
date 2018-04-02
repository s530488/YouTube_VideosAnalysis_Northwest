# YouTube_VideosAnalysis_Northwest
This project is a part of the course 44564-Data Intensive Systems at Northwest for Spring 2018 semester. This is being implemented by the group 2C of that course. This group has 4 develpors in total, which is a collaboration of two teams comprising of 2 members each. 

Teams Members:

Group 2C-Team 1: Vineeth Agarwal & Durga Charan Potukuru

Group 2C-Team 2: Ashok Atkuri & Raja Srikar Karthik Chinta

# Project Source Links
Repository: https://github.com/Vineeth-Agarwal/YouTube_VideosAnalysis_Northwest

Issue Tracker: https://github.com/Vineeth-Agarwal/YouTube_VideosAnalysis_Northwest/issues/1

# Introduction
The dataset includes data gathered from videos on YouTube that are contained within the trending category each day.

# Data Source
The data source contains two kinds of data files, one includes comments and the other includes video statistics. They are linked by the unique video_id field. It has category classification in .json and comments and videos list in .csv file formats.
The size of the data source is 148MB and it contains structured data.

# Data Source Link
https://www.kaggle.com/tripatsu/youtube-trending-videos-data-analysis/notebook

# Big Data Qualifications
# Volume : 
This data set contains huge set of comments and likes count and replies for each video in dataset and its size is about 148MB after decompressing the file.

# Variety: 
The data is all in text and special characters. Also there is a variety of languages involved in the comments. 

# Velocity: 
The dataset has the videos that are added to youtube every day with different tags and the number of views, and likes come to each video everyday. The other data set contains the comments that are posted every day for each video.

# Veractiy: 
There is no way to know if the data about comments or likes is authenticate because there is no check on a user profile that comments or likes.

# Value:
We can work on category based on tags and find the popular channel and trending topics in youtube. We have data for Great Britan and United States thus, we can find the sentiment analysis in a variety of forms, categorising YouTube videos based on their comments and statistics.

# Big Data Questions
For each cahnnel id tagged with Android, find number of views each video gets to determine the top 5 trending channels in android. (Vineeth)

For each category id, find the number of videos uploaded everyday to determine the tredning category. (Ashok)

For each video, find the number of views and likes it gets to determine the likeliness of a video by taking the ratio of views to likes. (Srikar Karthik)

For each video, find the sentiment of people for a video based on the emotions used in comments. The goal is to determine if video has positive, negative or neutral comments. (Durga Charan)

# Big Data Solutions
# Mapper input: 
jt2OHQh0HoQ,"To be there with a samsung phone\n😂😂😂",1,0
# Mapper Output/Reducer input
jt2OHQh0HoQ, 123,34

# Reducer output:  
jt2OHQh0HoQ 31%

# Language:  
Python 

# chart:
Bar charts and scattered plots.