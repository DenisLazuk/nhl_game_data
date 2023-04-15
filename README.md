# **Data Analytics Final Portfolio Project: NHL Game Data**
## Interpretation of game data from the National Hockey League

### Project Objectives:
- [x] Load the data
- [x] Prepare and clean the data
- [x] Analyze key statistics such as goals, shots, save percentage etc.
- [x] Make conclusions and communicate findings

### Technologies used:
```
Jupyter notebook
```

### Dataset used:
```
game.csv
game_teams_stats.csv
player_info.csv
game_goalie_stats.csv
team_info.csv
game_skater_stats.csv
```

### Libraries used:
```
pandas
seaborn
matplotlib.pyplot
numpy
```

### How to use ###
1. Import Libraries
1. Load the data
1. Clean the data
1. Analyze the data
1. Visualize the data
1. Make conclusions
1. Define further steps

### External links:
```
https://www.kaggle.com/datasets/martinellis/nhl-game-data?resource=download&select=game.csv

https://www.codecademy.com/journeys/data-scientist-aly/paths/dsalycj-22-bi-tools-for-data-scientists/tracks/dsalycj-22-final-portfolio-project/modules/dsaly-final-portfolio-project-c19c3552-f36d-4455-ae32-54093256f378/kanban_projects/data-analyst-final-portfolio
```

## Conclusions
**General**
1. Has the average number of goals per game increased over time?
    - The average number of goals per game started to steadily increase since season 2016/2017.
1. Has the average number of shots per game(1) increased over time?
    - The average number of shots per game started to increase since season 2002/2003
1. What is the goalie save percentage dynamic?
    - The average goalie save percentage per season increased from 89.7 in 2000/2001 season to 90.1 in 2019/2020 which is pretty much for such statistic.

**Specific**
**A. Defensive Stats**
1. Is larger number of hits good predictor for game winner?
    - Larger number of hits is not a good predictor for game winner.
1. How does the goalie power play save percentage effect the game outcome?
    - Expectedly higher goalie power play save percentage increases the chances of a team to win a game.
1. How do blocks effect the game outcome?
    - Larger number of blocks per game increases the chances of a team to win a game.
1. How does takeaways and giveaways effect the game outcome?
    - Takeaways slightly increase the chances of a team to win a game whereas giveaways doesn't have any effect.

**B. Offensive Stats**
1. How does power play percentage effect the game outcome?
    - If a team doesn't convert power play opportunities to goals most likely a team loses.
1. Is larger number of shots per game good predictor for game winner?
    - Larger number of shots per game increases the chances of a team to win a game.

**C. General Stats**
1. Is the larger number of penalty minutes good predictor for game loser?
    - Larger number of penalty minutes is not a good predictor for game loser.

**D. Advanced**
1. Do physical abilities of players like average team age or average height effect the performance of a team?
    - There is no significant difference in number of wins depending on height, weight or age. The only conclusions we can make that the prime years for hockey players lay between 26 and 29. Hockey players expectedly pretty big guys with the average weight of 88-96 kg and the height of 184 to 188 cm.
