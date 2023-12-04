## Youtube_Adview_Prediction
In the realm of YouTube advertising, content creators receive compensation from advertisers, contingent on both ad views and clicks generated for the promoted goods and services. To enhance the accuracy of ad view estimations, advertisers seek to leverage additional metrics such as comments, likes, and other relevant factors. Consequently, the objective is to develop and train diverse regression models, evaluating their performance to identify the most effective model for predicting the number of ad views.
## Input Data
The dataset "train.csv" encompasses information on approximately 15,000 YouTube videos, comprising metrics such as views, likes, dislikes, and comments. Additionally, details like the publication date, video duration, and category are included. The file also features a crucial metric, the number of ad views, serving as the target variable for prediction. To enhance algorithmic performance, it is imperative to preprocess and clean the data before inputting it into the models, ensuring more accurate and reliable results.

Click <a href="https://drive.google.com/file/d/1Cvy7blfe33Sv9it_tvS9uheYhzXAtQ1D/view?usp=sharing">here</a> to download the Train Data Set and click <a href="https://drive.google.com/file/d/1yXzLsro1S6yF1n_V2lYrRpD-InPe4cTx/view?usp=sharing">here</a> to download the Test Data Set

## Attribute Information
* 'vidid' : Unique Identification ID for each video
* 'adview' : The number of adviews for each video
* 'views' : The number of unique views for each video
* 'likes' : The number of likes for each video
* 'dislikes' : The number of likes for each video
* 'comment' : The number of unique comments for each video
* 'published' : The data of uploading the video
* 'duration' : The duration of the video (in min. and seconds)
* 'category' : Category niche of each of the video

## Objective 
To build a machine learning regression to predict youtube adview count based
on other youtube metrics.
