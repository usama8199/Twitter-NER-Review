# Problem Statement

Twitter is a microblogging and social networking service on which users post and interact with messages known as "tweets". Every second, on average, around 6,000 tweets are tweeted on Twitter, corresponding to over 350,000 tweets sent per minute, 500 million tweets per day.

Twitter wants to automatically tag and analyze tweets for a better understanding of the trends and topics without being dependent on the hashtags that the users use. Many users do not use hashtags or sometimes use wrong or misspelt tags, so they want to completely remove this problem and create a system of recognizing important content of the tweets.

**Named Entity Recognition (NER)** is an important subtask of information extraction that seeks to locate and recognise named entities.

We need to train models that will be able to identify the various named entities.

# Data Description

The dataset is annotated with 10 fine-grained NER categories: person, geo-location, company, facility, product,music artist, movie, sports team, tv show and other. Dataset was extracted from tweets and is structured in CoNLL format., in English language. Containing in Text file format.

The CoNLL format is a text file with one word per line with sentences separated by an empty line. The first word in a line should be the word and the last word should be the label.

Consider the two sentences below;

Harry Potter was a student living in london

Albus Dumbledore went to the Disney World

These two sentences can be prepared in a CoNLL formatted text file as follows.

Harry B-PER

Potter I-PER

was O

a O

student O

Living O

in O

London B-geo-loc

Albus B-PER

Dumbledore I-PER

went O

to O

the O

Disney B-facility

World I-facility

