## YouTube Adview Prediction
The goal of the project is to use Python to train various regression models and select the best one to predict the number of advertisement views.

## About the project
Youtube advertisers pay content creators based on adviews and clicks for the
goods and services being marketed. They want to estimate the adview based
on other metrics like comments, likes etc. The problem statement is therefore
to train various regression models and choose the best one to predict the
number of adviews. The data needs to be refined and cleaned before feeding
in the algorithms for better results.

## Data Description
train.csv - the training set
test.csv - the test set
The file train.csv contains metrics and other details of about 15000 youtube videos. 
The metrics include number of views, likes, dislikes, comments and apart from that published date, duration and category are also included. 
The train.csv file also contains the metric number of adviews which is our target variable for prediction.

### Attribute Information
- 'vidid' : Unique Identification ID for each video
- 'adview' : The number of adviews for each video
- 'views' : The number of unique views for each video
- 'likes' : The number of likes for each video
- 'dislikes' : The number of likes for each video
- 'comment' : The number of unique comments for each video
- 'published' : The data of uploading the video
- 'duration' : The duration of the video (in min. and seconds)
- 'category' : Category niche of each of the video

## Steps and Tasks
1. Import the datasets and libraries, check shape and datatype.
2. Visualise the dataset using plotting using heatmaps and plots. 
3. Clean the dataset by removing missing values and other things.
4. Transform attributes into numerical values and other necessary transformations.
5. Split the data into training, validation and test set in the appropriate ratio.
6. Use linear regression, Support Vector Regressor for training and get errors.
7. Use Decision Tree Regressor and Random Forest Regressors.
8. Pick the best model based on error as well as generalisation.
9. Save your model.