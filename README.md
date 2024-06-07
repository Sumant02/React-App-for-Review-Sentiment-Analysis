# Sentiment Analysis React App

## Starting the service
+ Install requirements with `npm install` & `pip install -r requirements.txt`
+ Download spaCy models with `python -m spacy download en`
+ Run `api.py` (will listen on 127.0.0.1:5000)
+ Run `npm start` in project directory (will host on localhost:3000)

## Changelog

**`Version 0.1.0`**
+ Changed NLP model from 1D Convolutional to BERT-based Gated Recurrent Unit (untrained)
+ Updated API to process calls using GRUBERT
+ Model now also includes class for tokenization

**`Version 0.0.2`**
+ Implemented callback function to update UI when sentiment score is returned
+ Implemented changing background colour on progress bar depending on score value
+ Fixed issue with API calls lagging behind state updates

**`Version 0.0.1`**
+ Basic static UI created
+ Created Flask API to return sentiment score from NN
+ API calls predict using pre-trained 1D CNN, trained on movie reviews. 
