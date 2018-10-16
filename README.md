# Fifa Rating Project - Author: Phil Nguyen

Data Description:

The data that we have is a combination of the two datasets: the players valuation of the 20 teams in English Premier League in the season of 2017/2018 dataset and the completed details of players in FIFA 18 dataset. The first dataset contains of basic information of players like the club that they play in, age, position, market value, Fantasy Premier League (FPL) value, and nationality. The second dataset contains of attributes of all the players in the game FIFA 18, such as pace, passing skills, shooting skills, dribbling skills, etc. All the attributes are quantified in a scale of 1-99. Both datasets are extracted from the public repository Kaggle.com, and are available for public use. We believe that the data from the combination of the two datasets are more than sufficient for us to do our analysis.

End-goals of the analysis:

Our main goal in this project is to apply the skills we learn in class in practice to build a multiple regression model to predict the values, both market value and actual value, of the players in English Premiere League. The potential predictors for the regression models are continuous variables like rated attributes, FPL values, popularity, age and other categorical variables like region, position, team, and international reputation. We want to have a comprehensive view of how soccer teams determine the price of a player, as well as compare the real-life value of the players to valuation indicators in other platforms like FIFA and FPL. In addition to the end goal that is the regression model, we also want to address some other interesting questions surrounding the data:
1. Are players in big clubs are over-valued compared to other clubs?
2. Popularity vs. Skills, which one affect the value of the player more?
3. Are defensive players (goalkeepers and defense) undermined in the game?
4. “Racism” in the game – Players in certain regions/countries are valued more?
Overall, with the rising influence of money in the game of soccer over the year, we believe the valuation of players is an interesting topic to explore. To be able to build a multiple regression model predicting the value would provide us a more thorough outlook of the money – soccer politics.
