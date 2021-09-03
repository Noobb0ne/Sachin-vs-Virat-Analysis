# Sachin-vs-Virat-Analysis
This is an statistical analysis of Virat Kohli and Sachin Tendulkar. 
We take five parameters for this comparison in a specified time frame different for each player:
  1. Runs Per Innings or RPI - Total Runs Scored / Total Number of Innings Played
  2. Strike Rate or SR - (Total Runs Scored / Total Balls Faced) x 100
  3. 100s Scored - Count of centuries scored
  4. 50s Scored - Count of half-centuries scored
  5. Team Contribution - (Total Runs Scored by player / Total Runs Scored By Batsmen) x 100. 

Since these two batsmen played in different eras we show the top 10 run scorers in the selected time frame and normalize the data.
Normalizing the five parameters will be as such:
  1. Runs Per Innings - We will take the ratio of total runs scored with sachin tendulkar / virat kohli by total runs without sachin tendulkar / virat kohli
  2. Strike Rate - We use the same logic as RPI. What we do is we calculate the SR with sachin tendulkar / virat kohli by SR without sachin tendulkar / virat kohli
  3. 100s Scored - We take the ratio of total number of innings sachin tendulkar/ virat kohli played by centuries scored by sachin tendulkar / virat kohli
  4. 50s Scored - Exact same logic as 100s scored just replace the no of centuries by no of half centuries
  5. Team Contribution - For this we take the ratio of runs scored by sachin tendulkar / virat kohli by runs scored by all other Indian batsmen
