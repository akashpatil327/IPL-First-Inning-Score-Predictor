### IPL-First-Inning-Score-Predictor
• This repository consists of files required to deploy a Machine Learning Web App created with Flask on Heroku platform.<br>
• Deployed App :   https://ipl-firstinning-scorepredictor.herokuapp.com/<br>
### Problem statement:

Build a model to predict the score (in terms of range) of any IPL match.<br>
### Dataset:

The dataset 'ipl.csv' consists of ball-to-ball informations about every match of IPL from Season 1 to 10 ie: (2008 to 2017)<br>
Dataset consists following columns:<br>
• mid: Unique match id.

• date: Date on which the match was played.

• venue: Stadium where match was played.

• bat_team: Batting team name.

• bowl_team: Bowling team name.

• batsman: Batsman who faced that particular ball.

• bowler: Bowler who bowled that particular ball.

• runs: Runs scored by team till that point of instance.

• wickets: Number of Wickets fallen of the team till that point of instance.

• overs: Number of Overs bowled till that point of instance.

• runs_last_5: Runs scored in previous 5 overs.

• wickets_last_5: Number of Wickets that fell in previous 5 overs.

• striker: max(runs scored by striker, runs scored by non-striker).

• non-striker: min(runs scored by striker, runs scored by non-striker).

• total: Total runs scored by batting team at the end of first innings.

### Dependencies:<br>

• Python - 3.7
• Scikit-Learn
• Pyforest
• Flask
• Pickle

### Algorithms Used:<br>

• Linear Regression
• Decision Tree Regression
• Random Forest Regression
• Ridge Regression
• Lasso Regression


