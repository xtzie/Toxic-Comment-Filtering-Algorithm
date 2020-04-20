## Introduction

_“F### off you anti-semitic c###”  
“She’s cute in an earthy kind of way. Can’t sing for sh## though”  
“F###### stupid a##. You have to apply for when when your 16 stupid f###”  
“Only a fool can believe such numbers. The correct answer lies between 10,000 to 15,000.”_  
  
It is unsurprising to see such comments above on the internet. Today, misleading and toxic comments abound. However, with the advances in machine learning, we can algorithmically:

- classify
- analyze
- ammend 

Such comments to make the internet a better place one constructive comment at a time. I used a kaggle dataset of Wikipedia commentst (https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) to build the model.

File run order:

1. Exploratory Data Analysis.ipynb - To understand context and distribution of the data
2. Data Cleaning & Topic Modelling.ipynb - To apply unsupervised learning to identify toxic comments
3. Comment Classification.ipynb - To build classification algorithms based on TFIDF and LDA topic features