Colab NoteBook- https://colab.research.google.com/drive/1XpwWaSdELr460ri-__BsthmQYB9RuUih#scrollTo=3KuIsaEwpo0u
# Problem Statement

Twitter is a microblogging and social networking service on which users post and interact with messages known as "tweets". Every second, on average, around 6,000 tweets are tweeted on Twitter, corresponding to over 350,000 tweets sent per minute, 500 million tweets per day.

Twitter wants to automatically tag and analyze tweets for a better understanding of the trends and topics without being dependent on the hashtags that the users use. Many users do not use hashtags or sometimes use wrong or misspelt tags, so they want to completely remove this problem and create a system of recognizing important content of the tweets.

**Named Entity Recognition (NER)** is an important subtask of information extraction that seeks to locate and recognise named entities.

We need to train models that will be able to identify the various named entities.

# Data Description

The dataset is annotated with 10 fine-grained NER categories: person, geo-location, company, facility, product,music artist, movie, sports team, tv show and other. Dataset was extracted from tweets and is structured in CoNLL format., in English language. Containing in Text file format.


# Models

1. Applied Attention + CRF + Sigmoid Focal Cross Entropy
2. Applied Re-Sampling + Pretrained BERT

# Result

1. Accuracy of the first model - 99%
2. Accuracy of the Second model - 98%

The thing to Note- Bert model has shown good f1 score category wise
