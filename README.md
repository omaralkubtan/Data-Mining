# World Cup Case Study
Using Historical World Cup Data to Perform Exploratory Data Analysis with MS Excel files and Python libraries (Pandas, plotly, numpy)

## Background Information
The World Cup is an international football competition organized by FIFA, the international governing body of football.
The competition is contested by the senior men's national teams who are members of FIFA.
The World Cup began in 1930 and takes place every four years except for 1942 and 1946 due to the World War.
Countries from all over the world participate in this competition regarded as the most prestigious tournament in football,
as well as the most viewed sporting event around the world. As of the 2014 World Cup, 20 tournaments have been held.
Each tournament is hosted by a previously nominated country for the duration of the competition.
The tournaments currently have a total of 32 participating countries. Nations are split into 8 groups of 4, and 2 teams qualify from each group.
After the group stages, the teams participate in single-game knockout rounds until the winner is determined.

## About Dataset
The Fjelstul World Cup Database is a comprehensive database about the FIFA World Cup created by Joshua C. Fjelstul,
Ph.D. that covers all 21 World Cup tournaments (1930-2018). The database includes 27 datasets (approximately 1.1 million data points) that cover 
all aspects of the World Cup. The data has been extensively cleaned and cross-validated.

Users can use data from the Fjelstul World Cup Database to calculate statistics about teams, players, managers, and referees.
Users can also use the data to predict match results. With many units of analysis and opportunities for merging and reshaping data,
the database is also an excellent resource for teaching data science skills, especially in R.

### Overview of the database
The 27 datasets in the Fjelstul World Cup Database are organized into 5 groups:

A first group of datasets (containing 9 datasets) includes information about each of the 9 basic units of observation in the database:
tournaments (tournaments), including the host country, the winner, the dates of the tournament, and information about the format of each tournament;
the FIFA confederations (confederations); teams (teams); players (players); managers (managers), including their team and home country;
referees (referees), including their home country and confederation; stadiums that have hosted World Cup matches (stadiums);
matches (matches), including the stage of the tournament, the location of the match (country, city, stadium), the teams involved, and the result;
and the individual awards that are handed out to players at each tournament (awards). Each of these units of observation has a unique ID number.

A second group of datasets (containing 4 datasets) maps teams, players, managers, and referees to tournaments.
There is a dataset about which teams qualified (qualified teams), which indicates how each team performed in the tournament;
a dataset about squads (squads), which indicates the name, position, and shirt number of each player;
a dataset about manager appointments (manager_appointments), which indicates the team and home country of each manager;
and a dataset about referee appointments (referee_appointments), which indicates the home country and confederation of each referee.

A third group of datasets (containing 4 datasets) maps teams, players, managers, and referees to individual matches.
There are datasets about team appearances (team_appearances), player appearances (player_apperances), manager appearances (manager appearances),
and referee appearances (referee appearances). Players who start a game on the bench but who are not substituted in appear
in the squads dataset but not the player_appearances dataset.

A fourth group of datasets (containing 4 datasets) cover in-match events, including: all goals (goals);
all attempted penalty kicks in penalty shootouts and their outcomes (penalty_kicks); all bookings (bookings), including yellow cards and red cards;
and all substitutions (substitutions). Each dataset includes the minute of the event and the player(s) and team involved.
Each of these 4 types of in-match events has a unique ID number.

A fifth group of datasets (containing 6 datasets) cover tournament-level attributes. There a dataset about host countries (host_countries),
including the performance of each host country; a dataset about the stages in each tournament (tournament_stages),
which records each stage of the tournament, the dates of the stage, and key features of the stage; a dataset about the groups in each group stage (groups),
which indicates the name of each group and the number of teams in each group; a dataset about the final standings in each group (group_standings);
a dataset about the final standings for each tournament (tournament_standings);
and a dataset about all individual player awards handed out at each tournament (award_winners).

### Accessing the data
The database is also available via an R package, which is available on GitHub. You can also download the database from GitHub in 4 formats:
an .RData version of the database is available in the data/ folder, a .csv version is available in the data-csv/ folder, a .json version is available
in the data-json/ folder, and a relational database version (SQLite) is available in the data-sqlite/ folder.

Accessing the codebook
The full codebook for the Fjelstul World Cup Database is available on GitHub. The codebook is available in .pdf format in the codebook/pdf/ folder.
It is also available in .csv format in the codebook/csv/ folder. There are 2 files: datasets.csv, which describes the contents of each dataset,
and variables.csv, which describes each variable.

### The license
The copyright for the original structure and organization of the Fjelstul World Cup Database and for all of the documentation and replication code 
for the database is owned by Joshua C. Fjelstul, Ph.D.

The Fjelstul World Cup Database and the worldcup package are both published under a CC-BY-SA 4.0 license. This means that you can distribute, 
modify, and use all or part of the database for commercial or non-commercial purposes as long as (1) you provide proper attribution and (2) any new 
works you produce based on this database also carry the CC-BY-SA 4.0 license.

To provide proper attribution, according to the CC-BY-SA 4.0 license, you must provide the name of the author ("Joshua C. Fjelstul, Ph.D."),
a notice that the database is copyrighted ("© 2022 Joshua C. Fjelstul, Ph.D."), a link to the CC-BY-SA 4.0 license
(https://creativecommons.org/licenses/by-sa/4.0/legalcode), and a link to this repository (https://www.github.com/jfjelstul/worldcup).
You must also indicate any modifications you have made to the database.

Consistent with the CC-BY-SA 4.0 license, I provide this database as-is and as-available, and make no representations or warranties of any kind 
concerning the database, whether express, implied, statutory, or other. This includes, without limitation, warranties of title, merchantability,
fitness for a particular purpose, non-infringement, absence of latent or other defects, accuracy, or the presence or absence of errors, 
whether or not known or discoverable.

## Check the `World Cup Case study.ipynb` file, which contains the case study with documentaion for each code.


