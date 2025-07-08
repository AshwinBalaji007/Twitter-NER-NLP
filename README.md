# Twitter-NER-NLP
## Problem Statement

Twitter is a microblogging and social networking service on which users post and interact with messages known as "tweets". Every second, on average, around 6,000 tweets are tweeted on Twitter, corresponding to over 350,000 tweets sent per minute, 500 million tweets per day.
Twitter wants to automatically tag and analyze tweets for better understanding of the trends and topics without being dependent on the hashtags that the users use. Many users do not use hashtags or sometimes use wrong or mis-spelled tags, so they want to completely remove this problem and create a system of recognizing important content of the tweets.
Named Entity Recognition (NER) is an important subtask of information extraction that seeks to locate and recognise named entities.
You need to train models that will be able to identify the various named entities.


## Data Description

Dataset is annotated with 10 fine-grained NER categories: person, geo-location, company, facility, product,music artist, movie, sports team, tv show and other. Dataset was extracted from tweets and is structured in CoNLL format., in English language. Containing in Text file format.
The CoNLL format is a text file with one word per line with sentences separated by an empty line. The first word in a line should be the word and the last word should be the label.

## Consider the two sentences below;

Harry Potter was a student living in london
Albus Dumbledore went to the Disney World
These two sentences can be prepared in a CoNLL formatted text file as follows.

1. Harry B-PER
2. Potter I-PER
3. was O
4. a O
5. student O
6. Living O
7. in O
8. London B-geo-loc
9. Albus B-PER
10. Dumbledore I-PER
11. went O
12. to O
13. the O
14. Disney B-facility
15. World I-facility
