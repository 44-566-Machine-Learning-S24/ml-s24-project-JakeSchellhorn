# Initial Explorations
In my initial explorations of the data there were no null values which made the dataset all that much easier to work with. I did however take the average salary feature of the player's contracts and divide it by 1,000,000, so it was easier to handle in visualizations as well as in the algorithms and scores. When I did my first looks into the features 3 of them caught my attention, points, assists rebounds. These are the usual statlines you see when a player is showcased for a game they played so I figured what better way to judge a player's contract then how they judge players for games and postseason awards. In doing this I created a quick comparison and correlation graph to see if these features were useful. Once I saw that these data features had good correlation to the average salary I decided to simplify these features as well. Instead of having thousands of points, assists, and rebounds to deal with I decided that to work with data I would create a per game stat for each feature. I took each feature and divided it by the games played for each player and saved that as a new feature to work with in the future.

<div align="center">
  <img alt="text" src="visualizations/initial correlations.PNG" width="500" height="500"><br>
  <sup>Correlation graph using Salary, Points, Assists, and rebounds<sup>
</div>

For more information about later models used click [here](ANALYSIS.md)
* [Source Code](initial_exploration.ipynb)
* [Repo]()
