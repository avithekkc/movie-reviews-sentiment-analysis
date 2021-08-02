



# Movie Reviews Sentiment Analysis
![Realtor Logo](https://github.com/avithekkc/movie-reviews-sentiment-analysis/blob/main/images/p4-header.jpg?raw=true)
## Overview
This project seeks to create a model that classifies Sentiment of a given movie review is Positive or Negative . This information will help Movie Production House to analyze reviews from viewers around various social networking platform.


## Business Problem
Movie Production House can get Average user rating of their movies from websites like IMDb, Google Reviews and Yelp. But to get the Overall Sentiment and Word Of Mouth from social networking sites can be quite painful as reviews are available in the form of text and not ratings (numbers). To solve this problem Machine Learning models that analyze the sentiment of a given text review can be helpful.

## Data

The Movie Reviews having ratings (1,2,3,8,9,10) were web scraped from IMDb.
Reviews with rating 1,2,3 were labeled as Negative and reviews with rating 8,9,10 were labeled as Positive.

250K Reviews were used for the analysis.

## OSMEN Process
 1. Obtaining data
 2. Scrubbing data
 3. Exploring data
 4. Modeling data
 5. Interpreting results

## INSIDE THE REVIEWS

### Word Cloud Of Positive Reviews
![Positive Word Cloud](https://github.com/avithekkc/movie-reviews-sentiment-analysis/blob/main/images/pos_wc.jpg?raw=true)

### Word Cloud Of Negative Reviews.
![Negative Word Cloud](https://github.com/avithekkc/movie-reviews-sentiment-analysis/blob/main/images/neg_wc.jpg?raw=true)

### Bigrams of  Of Negative Reviews. 

![Positive Bigram](https://github.com/avithekkc/movie-reviews-sentiment-analysis/blob/main/images/pos_bi.jpg?raw=true)

###  Bigrams Of Negative Reviews.

![Negative Bigram](https://github.com/avithekkc/movie-reviews-sentiment-analysis/blob/main/images/neg_bi.jpg?raw=true)
##  Results
2 classification models were performed to determine best fit:
Logistic Regression and Multinomial Naive Bayes.
The Logistic Regression Model reported to be the best model for predicting Sentiment from given movie review using TFIDF Technique.

ACCURACY : 93%  ( TRAIN) and 91%  ( TEST)

The WebApp version of the project can be found here - [Github](https://github.com/avithekkc/movie-review-sentiment-web-app)

##  Next Steps
-   Location, Time, Name and Numerals Stopwords can be use to reduced the the document length.  
-   Removing Low Occurring features.
-  Using Recurrent Neural Network to enhance the performance.


##   Repository Structure
```
├── datasets                            <- data used for the analysis.
├── images                              <- All images used throughout the project.
├── data-cleaning.ipynb                 <- Cleaning of data to create final dataset.
├── data-viz.ipynb                      <- Data Visualization.
├── BOW.ipynb		                    <- Modeling using bag of words.
├── TFIDF.ipynb		                    <- Modeling using TFIDF.
├── presentation.pdf                    <- Non Technical Presentation.
└── readme.md                           <- README file for Quick overview on project.
```
