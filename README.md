# NBA-All-Star-Analysis-Individual-Project-
Introduction​:
In the NBA, individual players are more important and popular than in other team sports due to basketball's smaller team size and game rules. 
This has made the NBA a star-driven league, with the all-star game highlighting the best players each season. This research aims to analyze the performance and legacy of these players over 42 years in order to discover the greatest all-stars in modern NBA history.​

Dataset: The dataset used is a representation of the season stats for each all-star from the years 1980-2022

Methodology​: The 3 main questions are:​

1. Who made the most all-star appearances between 1980-2022?​

2. Who were the players that only had one appearance?​

3. Out of all the all-star players, who has the highest career scoring average?​
   
Pandas, NumPy, and matplotlib were used to extract and analyze data. ​

Most All-star appearances​: 
To solve this question, we may need to use the group-by method (grouping player names) along with some aggregation. 
We will record each unique all-star year per player and add it to their specific summation, eventually using descending order. 

One All-star appearance​: 
This will be done with a similar method to the previous question, except with prioritization for players with a single appearance.​

Highest points per game​: 
The main method philosophy here will be calculating average and sorting them out. 
The points data will be considered numerical values, the mean of the scoring years will be calculated, and each cumulative scoring average will be compared in descending order. 

