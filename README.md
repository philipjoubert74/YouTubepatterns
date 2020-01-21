# YouTubepatterns
ML Dataset and ML model for prediction and suggestion of Content
This Repo is a collection of Youtube Dataset for views of Youtube Videos of Mindset Network.

The Dataset is specifically trying to extract patterns from Youtube Consumption Data of South African content in Mathematics, Science, Life Sciences and English.

The Youtube Channel is available at: https://www.youtube.com/channel/UC_ayO9NLpGuhCvxnWZ0KwYw?view_as=subscriber

The Data for the previous three years is used to have a fair model of trends through the year.

The Process so far is to:

1) Gather the raw CSV data from YouTube Studio
2) Group the data and identify useful labels, grouping and methods.
3) Visualising the trends within the data.
4) Cleaning the data, dealing with Zero values, excluding outliers and finding useful groups to average the values.
5) Splitting the data into training sets and testing sets.
6) Training the Model on Jupyter Notebooks compute models and on a single NVIDIA RTX 2070 GPU - to reduce errors of prediction.
7) Using extrapolation to apply to similar Videos in the 2020 future Video performance.
