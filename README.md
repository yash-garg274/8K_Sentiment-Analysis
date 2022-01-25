# 8K_Sentiment-Analysis

## What is 8-K

 Form 8-K is the “current report” companies must file with the Securities and Exchange Commission(SEC) to announce major events that shareholders should know about. 
 The companies file a 8-K report whenever significant corporate events take place that trigger a disclosure.
 
##  Problem Description

 The 8-K report might have positive, negative or a neutral event. To know whether the report is of positive type, negative type or of neutral type, we use sentiment analysis.
 The sentiment analysis calculates teh positive score and negative score and finds the difference to calculate the sentiment score.
 I have used the basic bag of words approach to calculate the sentiment score using the Loughran-McDonald Master Dictionary.
  
## Steps
  
 1) Extracting the url-link for 8-K, CIK no., data of filing of the report, from the EDGAR database.
 2) Downloading the 8-K, cleaning the data, and saving it in a repository.
 3) Applying the sentiment analysis to calculate the sentiment score.
