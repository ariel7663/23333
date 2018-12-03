# IEOR-4501 Session 002 - Final Project
# Group 23333

## Project discription
This project is designed as a Twitter Data Crawler, which takes a user's input of a specific twitter account, and returns several types of word map with the most frequently used words by this twitter user in his/her recent tweets. There are three types of wordmaps, a regular, a United States Flag, and a 'Love and Peace' map. Users can choose whichever he/she wants to print out.

We have included an example with President Donald Trump's twitter account (@realDonaldTrump) as a demo.

## Group Details
*group name:* 23333

*group members:* Ariel Liu, Yuqin Wang, Zihao Wang, Huanlun Li

*group github usernames:* ariel7663, yw3164, wangjwzh, hl3207(order as above respectively)

## Getting Started

These instructions will get you a copy of the project up and running on your Jupyter Notebook. 

### Prerequisites

```
Python 3.6
VM Software such as GCP
Jupyter Notebook (Online Preferred)
```
Python Packages imported from the libraries are listed in the [requirements.txt](https://github.com/ariel7663/23333/blob/master/requirements.txt).

### Installing

```
Clone git repository at "git@github.com:ariel7663/23333.git"
Run the Final.ipynb top down
```


## Run Instructions -Example running @realDonaldTrump

use Trump as an example and put screenshots here

Sample wordcloud output

First enter the username of the user you want to get all his/tweets

![alt text](https://github.com/ariel7663/23333/blob/master/Pictures/Sample%20input.png)


Then the program starts to scraping tweets and load the findings to a csv file

![alt text](https://github.com/ariel7663/23333/blob/master/Pictures/sample%20tweets%20loading.png)

By choosing from 3 different shapes, the user could either get a regular wordmap,

![alt text](https://github.com/ariel7663/23333/blob/master/Pictures/sample%20wordcloud.jpeg)

a US flag shaped wordmap,

![alt text](https://github.com/ariel7663/23333/blob/master/Pictures/sample%20flag%20world%20map.png)

or a Love and peace justure word map

![alt text](https://github.com/ariel7663/23333/blob/master/Pictures/sample%20peacenlove.jpeg)



## Acknowledgments

* Hat tip to anyone whose code was used
Citation:
* Wordmap tutorial
-url: https://www.datacamp.com/community/tutorials/wordcloud-python
-Website Title-DataCamp Community
-Article Title Generating WordClouds in Python
-Date Accessed December 03, 2018
* Scrape Twitter and api
-url: https://www.promptcloud.com/blog/scrape-twitter-data-using-python-r
-Website TitlePromptCloud
-Date Published September 24, 2018
-Date Accessed December 03, 2018


