# football_moneyball_21

<br>
## The Dataset
<br>
In this project the data has been taken from a Kaggle repository:
<br>https://www.kaggle.com/ekrembayar/fifa-21-complete-player-dataset?select=fifa21_male2.csv
<br>The data has been scrapped from sofifa.com and shows the players info based on the popular video game.

<br> The data contains players and many stats about them.

<br> ## My project
<br> 
This was a simple project that tries to find a replacement of a single player. For this we choose a team: Sevilla FC
and from that team we choose a player who is likely playing at this moment and whos contract is about to expire.
<br><br>
This is the reason that Sergio Escudero was the player choosen.

<br><br>
From here a model was contructed based on how the 20 teams spent the most money in their team (probably also the best teams) 
decided the players in the same position as Escudero.

<br><br>
For the model it was not considered wether the player was playing on the right side or on the left side 
of the court. This helps us get more info about this sort of players. 

<br><br>
Then a simple regression model was used to create a model. And using a threshold in the colinearity of the
model help us figure out 4 factors which influenced the most on the decission of those players.

<br><br>
Using the rscore of those 4 factors we multiplied it by the data found in the columns of those factors, for the candidates
players. With that an overall score was created to calculate which player will be the most efficient.
