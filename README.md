# Introduction

Fantasy Premier League (FPL) is a Fantasy Soccer game based on the English Premier League (EPL). The EPL is a soccer league in England. It is at the highest level in the English league system hierarchy. A league season typically runs from August to May and is contested by 20 teams. Each team plays every other team twice over the course of a season, home and away. This league is the most watched league in the world with an estimated audience of almost 4.7 billion people. 
It also has the highest revenue of any soccer league in the world, making it one of the most lucrative organizations in the world. Consequently, FPL is also the largest fantasy soccer game in the world with almost 11.5 million players in 2023. It is owned and operated by the EPL.
In FPL, players need to create a soccer team of 15 real life soccer players from the EPL every game week. This team consists of a starting eleven and 4 substitutes. The starting eleven is then given points every week based on the real-life statistical performance of the players. Based on the points scored every week, players can gain real life prizes. The grand prize includes a paid trip to England with VIP tickets to a real soccer match of their choice in the EPL. The winner of the grand prize is the player with the highest cumulative points over the entire season which consists of 38 game weeks in total.
Team selection for each game week can be a difficult task considering players need to evaluate hundreds of soccer players who are currently playing in the EPL and analyze their past performance to arrive at a potential best eleven.

# Data
The dataset has been procured from the official API of the premier league.
-	Source: https://fantasy.premierleague.com/api/bootstrap-static/
-	Size: 1870 rows and 31 columns
-	The data spans 2015/16 to the 2022/23 season.
-	Descriptive Features:
    - season_name: The year of the season.
    - element_code: A unique identifier for each row.
    - start_cost: Starting cost of the player.
    - end_cost: Cost of the player at the end of the season.
    - minutes: Number of minutes played in the season.
    - goals_scored: Number of goals scored in a season.
    - assists: Number of assists recorded in a season.
    - clean_sheets: Number of clean sheets over a season.
    - goals_conceded: Number of goals conceded in a season.
    - own_goals: Number of own goals scored in a season.
    - penalties_saved: Number of penalties saved in a season.
    - penalties_missed: Number of penalties missed in a season.
    - yellow_cards: Number of yellow cards accumulated over a season.
    - red_cards: Number of red cards accumulated over a season.
    - saves: Number of saves recorded over a season.
    - bonus: Total bonus points in a season.
    - bps: Bonus points system.
    - influence: Influence is a metric that reflects a player's ability to make a difference in a match.
    - creativity: Creativity measures a player's ability to provide goal-scoring opportunities for their teammates.
    - threat: measures a player's goal-scoring threat during a match.
    - ict_index: ICT stands for "Influence," "Creativity," and "Threat," and the ICT Index is a combined metric that takes into consideration these three factors to assess a player's overall impact on a match.
    - starts: Number of starts afforded to the player.
    - expected_goals: Expected Goals (xG) is a statistical measure that quantifies the likelihood of a goal being scored from a particular goal-scoring opportunity.
    - expected_assists: Expected Assists (xA) is a statistical measure that quantifies the likelihood of a player providing an assist based on the quality of their pass or involvement in a goal-scoring opportunity.
    - expected_goal_involvements: Expected Goal Involvements (xGI) is a combined metric that represents the sum of a player's Expected Goals (xG) and Expected Assists (xA).
    - expected_goals_conceded: Expected Goals Conceded (xGC) is a metric that estimates the number of goals a team or defense is expected to concede based on the quality and quantity of the opposition's goal-scoring chances.
    - player_id: Unique identifier for each player.
    - first_name: First name of the player.
    - last_name: Last name of the player.
    - position: The position on the pitch.
- Target Feature: 
-	total_points: Total points accumulated over the season.

# Data Visualization
![image](https://github.com/sanchitd9/fpl_prediction/assets/38399292/1d0fc70c-6c1a-4676-8146-ac96bc1f785b)

![image](https://github.com/sanchitd9/fpl_prediction/assets/38399292/07bf6853-79f1-4c02-94f4-d7608464ce06)


