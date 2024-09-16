# Data-Analysis-Formula-1
Analysis of the Formula 1 World Championship results of the 2008 season

The project involves the implementation of the following functions:

1. Function for the analysis of individual driver performances 
The first function receives as input the name of a driver and returns a list containing three key pieces of information: - The total points accumulated by the driver during the championship. - The number of wins, i.e. how many times the driver came first in a Grand Prix. - The number of podiums, i.e. how many times the driver finished in the top three.
This function will be useful to analyse the individual performances of the drivers and get a clear view of their positions during the season.

2. Function for Creating the Final Ranking of Drivers 
The second function generates a dictionary containing the names of the drivers as keys and their total score as values. The dictionary is then used to create an overall ranking of the drivers.
Finally, the ranking will be saved in a text file (Drivers_Standings_2008.txt) with the following format:

Drivers Standings 2008 Formula 1 DriverName1: ScoreTotal DriverName2: ScoreTotal

3. Constructor Ranking Function 
The third function creates a dictionary with the team/constructor names as keys and their total score as values. Each team's score is the sum of the points obtained by the drivers who competed for that manufacturer.
This function uses the data previously generated for the drivers and calculates the manufacturers' ranking. This information is also essential for a clear view of the teams' performance during the year.
