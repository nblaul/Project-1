# Project-1
PROPOSAL: Our project is to compare trends in player performance in the NFL in various types of weather, specfically focusing on temperature and precipitation-type.  We will examine the relationships between player stats and weather at the time of the game in one season, excluding pre-season and the superbowl. 

TEAM:
Nick and Dan : Clean data and create CSV for game and stats data
Arnaz and Jennifer : Clean data dn create CSV for weather data
TBD : Consume data and analysis
Joanne: Create charts from Data
Joanne: Slides for presentation



EXTRA: 
Set a standard measure of success for the position QB
Column B = Completions, Column C = Attempts, Column D = Passing Yards, Column E = Touchdowns, Column F = Interceptions
Column G = Passer Rating
Passer rating =IFERROR((((IF((((G2/H2)-0.3)*5)>2.375,2.375,IF((((G2/H2)-0.3)*5)<0,0,((G2/H2)-0.3)*5)))+(IF(((I2/H2)-3)*0.25>2.375,2.375,IF(((I2/H2)-3)*0.25<0,0,((I2/H2)-3)*0.25)))+(IF((((J2/H2))*20)>2.375,2.375,IF((((J2/H2))*20)<0,0,(J2/H2)*20)))+(IF(2.375-((K2/H2))>2.375,2.375,IF(2.375-((K2/H2))<0,0,2.375-(K2/H2)))))/6)*100,0)
