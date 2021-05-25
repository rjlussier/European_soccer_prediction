# European Soccer Prediction
Repo for predicting soccer success based on spatio-temporal data.

### Problem Statement
European soccer  is big business. The ‘big five’ leagues, made up by England, Germany, Italy, Spain and France posted $17.4 billion USD revenue for the 2017/18 season, an increase of 6% from the previous year. Increasing team performance can have a direct impact on revenue by increasing viewership and increasing prize money awarded at the end of the season. Currently analysis is performed manually and teams spend a lot of effort reviewing tapes to identify winning tactics and strategy. Automating this process would provide value to teams by increasing the quality of the analysis and even being able to predict the impact changing tactics or scouting a new player will have on their performance.

### Raw Data
Some of the data files are too large for uploading to github. If you'd like to explore them, with my project code they can be downloaded from the following link.
https://figshare.com/collections/Soccer_match_event_dataset/4415000/3

### [Data Wrangling](https://github.com/rjlussier/European_soccer_prediction/blob/master/Soccer_Data_Wrangling.ipynb)

### [Exploratory Data Analysis](https://github.com/rjlussier/European_soccer_prediction/blob/master/Soccer_EDA_Data_Story.ipynb)
First let's see which how each Premier League team fared in terms of wins/draws/losses over the season. We see that Manchester City lead the league while West Bromwich Albion (WBA) was in last place.
![WDL Histogram Image](data/WDLHistogram.png)

Comparing the distribution of events accross the football pitch between Manchester City and West Bromwich Albion. This comparison shows Manchester City playing a more offensive game whereas WBA seems to play more of its games on the defense. 
![Event Distribution Comparison Image](data/PitchEventDistributionComparison.png)

### [Machine Learning](https://github.com/rjlussier/European_soccer_prediction/blob/master/Soccer_Machine_Learning.ipynb)
