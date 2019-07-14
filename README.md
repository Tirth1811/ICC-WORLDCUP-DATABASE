# ICC-WORLDCUP-DATABASE
Database Title : Database for keeping Match and Team records of past ICC-World Cups 

Scope of Database: 
It involves keeping all the the records of matches played in any ICC world cup till now : 
Category of the match, two teams between which the match was played, place where match was organized, Man of the match, winning team of that match, total runs made by each team,total wickets taken by each team, total overs played by each team, details of umpires in that particular match, extra runs earned by each team.

Details of team:
Country name  and captain, vice captain and  for that team for particular world cup. 

It includes details of players from different teams : 
Name of the player, player id, category of the player and which country he is presenting for, ODI ranking ,total runs , total balls played , sixes , fours ,  average , strike rate, half centuries, centuries , no. of matches ,no of innings , overs ,wickets taken by the player , economy , avg. bowling speed , fastest bowling speed.

It also includes performance of batsmen in world-cup match : 
	Runs made by each batsman , balls , sixes , fours , type of dismissal
, name of bowler who took his wicket , if he was caught-out then the player who took his catch , strike-rate.
 
It also includes performance of bowlers in world-cup match :
 Wickets taken by bowlers , no. of overs thrown , no. of maiden overs  , no. of dot balls , economy , highest bowling speed , no. of wides and NO balls.

Details of World cups like where it was held and man of the series of particular cup can be retrieved also. Teams’ ICC ranking, captain, vice captain of the team are included too.

Details of Umpire like name of umpire,his country name and total umpired matches.

Details of Coach like name of coach,the country name he works for in each worldcup and name of country which he belongs.

Details of stadium like name of stadium and location of that stadium( city  and country ) and capacity of the stadium.
  

Description: 
World Cup is organized by ICC(International Cricket Council) once in every four years. Different countries from all over world participate in world cup. Each country can be represented by only one team. ICC World Cup was started back in 1975. Host nation can be different for every world cup like  England, India, South Africa, West Indies, Bangladesh etc have hosted the world cup till now.

For players we are storing his player id, name, position of the player and which team he belongs to. For position there could be batsman, bowler and all rounder. Every player can be part of only one team.It also includes player’s ODI ranking. After every match, total runs made by player updated by adding the runs of recent match.

A balanced team consists of 11 players but injury or any other reasons are exceptions. Every team has to have one captain and one vise captain. We also update the ICC ranking of the team in every world cup. ICC ranking of a team can differ in different world cups like India had 1st rank in 2011 but it had 2nd rank in 2003.
 
Database also includes information of every matches in worldcup. Every match should have unique match id. Match also has attribute called category which can have values like {final , semi-final, quarter-final, group match}. It also includes two teams which played that match and winner of that match must be from those two teams. 
