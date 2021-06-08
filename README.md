# Data Science Immersive Capstone 1
Modeling review score data and using Welch's T-Test to determine if player base scope impacts review scores.
    
### Introduction

<img src="https://user-images.githubusercontent.com/25779351/121104193-20f0bf80-c7c7-11eb-8472-fb78aa5bbead.png" alt="Hollow Knight" width="500" height="350">  <img src="https://user-images.githubusercontent.com/25779351/121104211-2b12be00-c7c7-11eb-83e3-49fb80ac04b1.png" alt="Halo" width="500" height="350"> 


Video games are immensely popular entertainment products with the industry seeing billions of dollars in revenue annually.  As someone who enjoys them I wanted to see how others view and play games and make decisions on which to purchase.  I chose 2 games for the project Halo and Hollow knight, which are both popular games with diffrent player scope and different play styles.  Hollow knight is an indie style 2d "platform" game with a higher entry barrier utilizing tight controls and a higher difficulty. Halo is a 1st person shooter and a triple A production game with great graphics and an innovative style of gameplay and player interaction.  Hollow knight being "indie" (or niche) and Halo being "Triple A" is the main distinction I wanted to observe. Halo had more purchase and downloads, but the reviews for Hollow Knight were more positive. So how do popularity and broad appeal relate to consumer ratings?
    
The review data for HALO and Hollow Knight was gathered from the Steam platform API, and it included the reviewer id, positive or negative review of the game, and a vote count of other users perception of the review which contributed to a voter score.  As people find a review helpful the score increases helping good reviews rise to the top.

Welch's T-Test was chosen because the population variance is not known. 
Null Hypothesis: The mean of a player's rated score for a niche game is equal to the mean of a "broad appeal" game.
Alternate Hypothesis: The two means are statistically different.

Likes vs. Dislikes:

<img src="https://user-images.githubusercontent.com/25779351/120391806-3496b480-c2f5-11eb-915f-9322bd2fd29a.png" alt="Likes vs. Dislikes" width="500" height="350">

Mean Weighted Scores:

<img src="https://user-images.githubusercontent.com/25779351/120391849-437d6700-c2f5-11eb-8320-ecb79e05b855.png" alt="Likes vs. Dislikes" width="500" height="350">

Performing the test resulted in a statistic value of 2.52, and a p-value of .012 meaning the Null Hypo-Thesis can be rejected

