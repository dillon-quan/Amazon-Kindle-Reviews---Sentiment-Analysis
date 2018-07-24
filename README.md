# Amazon-Kindle-Reviews-Sentiment-Analysis

### Summary

This notebook contains code I used to explore the Amazon Kindle Reviews dataset from Kaggle. This dataset provides text reviews on books written by Amazon Kindle users along with an explicit rating between 1-5. The goal of this notebook is to preprocess the written text to develop models to predict users sentiment towards the products. Given the explicit scale, the sentiments are divided by ratings where ratings between 3-5 would be classify as Enjoyed (binary one) the book while ratings 1-2 would be classify as disliked (binary zero).

### Text Preprocessing

1. Remove all Punctuations
2. Remove all non alphabetical words
3. Lowercasing all words
4. Remove all english stopwords
5. Lemmatization to reduce words to their base form

### Results

All algorithms that were tested provided similar results. 

![image](https://user-images.githubusercontent.com/35437033/43147732-8b619136-8f18-11e8-8456-b20485576774.png)


### Dataset

https://www.kaggle.com/bharadwaj6/kindle-reviews/home
