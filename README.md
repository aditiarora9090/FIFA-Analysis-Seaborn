# FIFA 22 - EDA using Seaborn

## About the dataset

The FIFA22 dataset contains all key attributes, and features of male football players around the world. 

In football, player positions corresponds to these positions:-
![](https://www.fifplay.com/img/public/positions.jpg)

In this dataset, we have 1 row each for every football player in the game FIFA 22, For every player we have :-

-   Name
-   Weight
-   Height
-   Salary
-   Overall (This is an overall score of how good the player is)
-   Potential (In FIFA, if you play career mode, players evolve and their overall scores improve, potential refers to how good a player can get, not what he is currently)

Then we have most other options like:-

-   Heading (How well can the player head the ball)
-   Standing tackle (How well can the player do a standing tackle - defense)
-   Sliding tackle (How well can the player do a sliding tackle - defense)

And many many more 

## Exploratory Data Analysis

I have done Exploratory Data Analysis on this dataset and found some interpretations which are listed below:
- The overall rating of the players is normally distributed
- There is a direct relationship between potential and wages i.e higher the potential, higher the wages in EUR of the people. Also, we can see that people with higher wages also have higher international reputation.
- Players with higher age prefer using their right foot for playing the match.
- L. Messi is the best football player with the highest number of overall rating, followed by R. Lewandowski and Christiano Ronaldo.
- K. De Bruyne and K. Benzema are the richest players with the highest wages of approximately 350000 EUR.
- K. Miura is the oldest player with the age nearly 55 years.

## Selection of the best players

Now, I did some analysis to find out the best player in the following categories:

 -  **GOALKEEPER**
   > This was selected based upon the following KPI's:
   > 1.  goalkeeping_diving
   > 2.  goalkeeping_handling
   > 3.  goalkeeping_kicking
   > 4.  goalkeeping_reflexes
   > 
   ***G. Donnarumma** has the best diving, handling and reflexes and is also the 4th best player in goal kicking. He is also young with age of 22 years, So I feel this player should be scouted for goalkeeping.* 
 -  **DEFENDER** 
   > This was selected based upon the following KPI's:
   > 1.  defending_marking_awareness
   > 2.  defending_standing_tackle
   > 3.  defending_sliding_tackle
   > 4.  defending
   > 
***Ruben Dias** has the best marking awareness and defending and is also the 2nd best in defending sliding tackle. He is also young with age of 24 years, So I feel this player should be scouted for defending.*
 -  **MIDFIELDER** 
   > This was selected based upon the following KPI's:
   > 1.  passing
   > 2.  dribbling
   > 3.  skill_ball_control
   > 
***K. Mbappé** has the best passing and ball control. So, I would like to scout him for the midfielder position.*  
 -  **ATTACKER**
   > This was selected based upon the following KPI's:
   > 1.  shooting
   > 2.  passing
   > 3.  attacking_short_passing
   > 4.  movement_reaction
   >
  *I would like to appoint **Bruno Fernandes** to be scouted for the Attacker has he has the highest overall passing and attacking short passing levels and is also amongst the top 5 players in terms of shooting and movement reactions.*  
  
