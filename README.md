# BERTweet Language Model Sentiment Classifier

#### Table of contents
1. [Introduction](#introduction)
2. [Main results](#results)
3. [Using BERTweet with `transformers`](#transformers)
    - [Pre-trained models](#models2)
    - [Example usage](#usage2)
    - [Normalize raw input Tweets](#preprocess)
4. [Using BERTweet with `fairseq`](#fairseq)



BERTweet is the first public large-scale language model pre-trained for English Tweets. BERTweet is trained based on the RoBERTa pre-training procedure. The corpus used to pre-train BERTweet consists of 850M English Tweets (16B word tokens ~ 80GB), containing 845M Tweets streamed from 01/2012 to 08/2019 and 5M Tweets related to the COVID-19 pandemic.


This is a implementation of the Bertweet language model for sentiment classification of tweets. 
  The fine-tuning precedure is depicted visually in the graph below. 
  This model Achieved state of the art results (73% Accuracy) based on the SemEval task7a benchamrk. 

![ScreenShot](/Figures/Figurex.png)
