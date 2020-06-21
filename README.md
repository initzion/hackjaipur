## :rocket:  sentimentZION :rocket:
-- a project by initZION 2020.

![Python](https://img.shields.io/badge/Python-^3.8-blue.svg?logo=python&longCache=true&logoColor=white&colorB=5e81ac&style=flat-square&colorA=4c566a)
![Flask](https://img.shields.io/badge/Flask-1.1.2-blue.svg?longCache=true&logo=flask&style=flat-square&logoColor=white&colorB=5e81ac&colorA=4c566a)
![Pandas](https://img.shields.io/badge/Pandas-v1.0.3-blue.svg?longCache=true&logo=python&longCache=true&style=flat-square&logoColor=white&colorB=5e81ac&colorA=4c566a)
![Dash](https://img.shields.io/badge/Dash-v1.11.0-blue.svg?longCache=true&logo=python&longCache=true&style=flat-square&logoColor=white&colorB=5e81ac&colorA=4c566a)
![Plotly](https://img.shields.io/badge/Plotly-v4.6.0-blue.svg?longCache=true&logo=python&longCache=true&style=flat-square&logoColor=white&colorB=5e81ac&colorA=4c566a)
![GitHub Last Commit](https://img.shields.io/github/last-commit/google/skia.svg?style=flat-square&colorA=4c566a&colorB=a3be8c)


## SentimentZION
We at Sentiment ZION are focused to paint the true picture of the world for you. The information that is provided is mined from social media and analyzed by us, we provided an overview of data from websites like Youtube, Twitter, and Reddit about your topic for a relevant timeframe.
This data is presented in a visual format that provides higher readability and ease of consumption.

![SentimentZION Thumbnail](https://github.com/initzion/hackjaipur/blob/master/assets/img/thumbnailhj.jpg)
 https://www.youtube.com/watch?v=PdQlbfJ3SBY&feature=youtu.be
 
## Rightly said, Diversity is the inclusion of all individuals as technology and that is where our website focuses on!!!

## What am I seeing?
Graphs that depict the analysis of the sentiments of the people.

## What is the source of the data collection?
These data are collected from the comments of social media sites like YouTube, Twitter, and Reddit.

## How is the data analyzed?
The most important part of our website is the analysis of the data. The comments that are retrieved are analyzed through a sentimental analysis model which rates the comments from a scale of -1 to 1. -1 being most negative, 0 being neutral and 1 being most positive.

## How far is the data correct?
The data is as efficient as it could be. The comments are analyzed through text blob Natural Language Processing(NLP). So the output is quite efficient.

## What is the significance?
Most social networks project the views of the most vocal but a minority of users on their platforms, however, the majority of the users' opinion is not taken into consideration. That is where our website effects the most.

## The comments are updating! Are the graphs getting updated?
Yes, the graphs are the live visual representation of the comments. As the comments get updated, the graphs to get updated.
Sentiment Analysis
 
 ## :pencil: Note
 Edit 2 files "youtube.py" , "senti.py" and "Reddit.py"
 Enter your own api-key if you dont have one visit:
 Edit the credential of Auth0 in hackjaipur/login
 
 for ibm: https://developer.ibm.com/technologies/iot/tutorials/iot-generate-apikey-apitoken/
 
 for youtube: https://developers.google.com/youtube/v3/getting-started
 
 for reddit : https://www.reddit.com/prefs/apps
 
 **Note: You need to integrate your own Auth0 credentials. Check this out at https://auth0.com/

## :heavy_check_mark: Installation :heavy_check_mark:


**Installation via `requirements.txt`**:

```shell
$ git clone https://github.com/initzion/hackjaipur.git
$ cd hackjaipur
$ python -m venv myenv
$ source myenv/bin/activate
$ pip install -r requirements.txt
$ python app.py

On a new terminal tab:

$ cd hackjaipur/login
$ pip install -r requirements.txt
$ python server.py

-----
