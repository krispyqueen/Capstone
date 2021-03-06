Next Word Prediction - Capstone Project
========================================================
author:Bipika Amatya 
date: 2016-04-12

Introduction
========================================================

The objective of the App is implementing a predictive model that offers hints to one or more words, coherent to the sentence that�s been input by its user. The Capstone dataset used includes twitter, news and blogs from HC Corpora. After performing data cleansing, sampling and sub-setting, we gather all data in R data frames. Applying some Text Mining (TM) and NLP techniques, is created some set of word combinations (N-grams). These are the main support to Katz Backoff algorithm predicts the next word. Some adaptations and heuristics were specially developed to enhance this Shiny application.

Build Prediction Model
========================================================

This project is to create a shiny App to predict next word based on previous input, using n-grams models, which are built in following steps:

- Read millions lines content from news, blogs and tweets
- Break each source into sentences
- Removed special characters, numbers, punctuation and profanity
- Built basic 4-gram model for predicting next word based on the previous 1, 2, or 3 words
- Split off last word from each n-gram as Next-Word


How the app works
========================================================

- Go to the shinyapp [https://bipika.shinyapps.io/capstoneshiny/].
- Type any word in the given textbox.
- There is an existing text as well. "Give it a".
- Above the textbox are the 3 predicted words.
- Press "Predict" button to predict the next one.

Further Details:
========================================================

- ShinyApp (https://bipika.shinyapps.io/capstoneshiny/)
- Github (https://github.com/krispyqueen/Capstone/tree/master/SHINY)
