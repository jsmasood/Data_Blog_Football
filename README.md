# Data Blog - Exploring Home Advantage in Football

A data blog I wrote using Python to analyze football data.

### Contents:

#### * Introduction
#### * Data Source
#### * Libraries
#### * Main Findings

-----------------------------------------------------------------------------------------------------------------------


##### 1. Introduction

This data blog has been written for the Udacity Data Science nanodegree program.

As a fan of football (what some might also call soccer) I was interested in doing some analytics on football data. Specifically my question is how important is home advantage in football and whaat role does it play?

The blog is available online at https://www.kaggle.com/junaidsadiqmasood/exploring-home-advantage-in-football


##### 2. Data Source

In order to probe this question I used data from the leagues in eleven European countries, covering eight seasons (2012-2016).
The data is publically available at https://www.kaggle.com/hugomathien/soccer


##### 3. Technologies

Project is created with:
* Python version: 3.6

I also used the following libraries for this project.

* SQLite3 - To read the data
* Pandas & Numpy - For data analysis
* Matplotlib & Seaborn - For basic charts
* Geopandas & Descartes - For managing geodata needed for European map
* IO - For managing input/output streams for interactive map
* Bokeh - For creating interactive map of Europe

##### 4. Main Findings

* The home team is twice as likely to win as an away team.
* The percentage of home teams winning games has fallen slightly across 8 seasons.
* There is no geographic pattern to home team advantage across Europe.
* On average, the top 2 teams in the English Premier League have the similar away records and the title goes to the team with the better home form.
* The winner on average gets 
* Conversely away form is crucial for teams at the bottom, and a couple of good away results can be the difference between safety and relagation.
