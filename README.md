# 23333
IEOR4501 Project
**A description of what has been implemented**
This project is designed as a Twitter Crawling, which takes a user's input of a specific twitter account, and returns a word map with the most frequently used words by this twitter user in his/her recent tweets.
We have included an example with President Donald Trump's twitter account (@realDonaldTrump) as a demo.


**Group detail**
*group name:* 23333
*group members:* Ariel Liu, Yuqin Wang, Zihao Wang, Huanlun Li
*group github usernames: ariel7663,yw3164,wangjwzh,hl3207(order as above respectively)

**Instructions**
packages to install/import:
import tweepy
import csv
import numpy as np
import pandas as pd
from wordcloud import WordCloud
import matplotlib.pyplot as plt
from os import path
from PIL import Image
import nltk
from nltk.corpus import stopwords
import wordcloud

**Run instructions**
use Trump as an example and put screenshots here

Sample wordcloud output
First enter the username of the user you want to get all his/tweets
![alt text](23333/Sample input.png)
Then the program starts to scraping tweets and load the findings to a csv file
![alt text](23333/sample tweets loading.png)
By choosing from 3 different shapes, the user could either get a regular wordmap,
![alt text](https://github.com/ariel7663/23333/blob/master/sample%20wordcloud.jpeg)
a US flag shaped wordmap,
![alt text](23333/sample flag world map.png)
or a Love and peace justure word map
![alt text](23333/sample peacenlove.jpeg)


      