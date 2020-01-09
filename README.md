# Predicting_European_Soccer_Matches

Abstract

Sports analytics has boomed in recent years with the explosion in available data to data. One of the biggest analytic interests is predicting the results of games. Soccer, the world's most popular sport, is full of data for this kind of analysis. This report will look into predicting various game outcomes for European soccer games using player rating data from EA Sport's FIFA video game series. The expected goal differential and total goals scored will be modeled using multiple linear regression and support vector machines. Win probabilities will be predicted using t-stat and poisson distributions. Finally, projected final standings will be created using these models. The goal for this report is to use these modelling methods to create reliable models for creating these outcomes. All of these game outcome predicitons are important to all kinds of people from front office executives to coaches to sports bettors. Given how much money is tied up into soccer, it is important for everyone involved to have the most accurate analytic information.

-------------------------

This is the project I submitted for my senior capstone at Case Western Reserve University. I got all of the data from open sourced Fifa and soccer match data sets found on Kaggle. The entire project was done using R code and a little bit of Excel.

-------------------------

Predicting_European_Soccer_Matches.pdf is the knitted final pdf report. It includes the background, methodology, and results of the project

Predicting_European_Soccer_Matches.rmd is the r code for the report.

Data_Cleaning.rmd is the file where I did the majority of my data cleaning and processing, as referenced in the report.

FIFA17.csv, FIFA18.csv, and FIFA19.csv are the Fifa video game data sets from Kaggle

match_results.csv is a condensed version of the match data set from Kaggle (original is very large, so I removed many unneeded misc. variables so it could be uploaded)

all.csv is the data set I created with all of the rating data for each team. For simplicity (and the time consuming nature of trying to find starting lineups for 19,314 games), I created team "rosters" using the best goalkeeper, 2 forawards, 4 midfielders, 4 defenders, and the 7 best remaining players for the bench. Full methodology is in the report.

games.csv is the data set I created with statistics from each game as well as the aggregate ratings for each team competing in the match. This is the data set used to create the models

convert17.csv, convert18.csv, and convert19.csv are team name conversions I made manually. The names for many of the teams differ slightly between all of the data sets, so they all needed to be converted to one common name.

poissonexample.csv and poissonexample2.csv are used as demos within the report

testing.csv and training.csv are copies of the training/testing samples I used in the report.

presentation2.html and presentation3.html are my second and third 5-minute project update presentations.
