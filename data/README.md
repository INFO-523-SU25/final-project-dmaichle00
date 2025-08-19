# Data
-   **[nfl_2024_games_with_dvoa]**: This dataset is a combination of data pulled into the project using the nfl_data_py

# Codebook for [chosen] Dataset
https://github.com/nflverse/nfl_data_py/blob/main/data/schedules/2021.csv
## Variable Names and Descriptions:

-   **variable**: Description
-   **game_id**: Game Identifer in the format Year_Week_Away_team_home team
-   **season**: What season is this entry from IE. 2024 season
-   **week**: What week number is the game being played on
-   **away_team**: 2 or 3 letter trigraph indicating the visiting team
-   **home_team**: 2 or 3 letter triagraph indicating team playing at home
-   **away_score**: Number of points scored by away team
-   **home_score**: Number of points scored by home team
-   **gameday**: Contains date the game was being played
-   **roof**: Indicates whether the game was played indoors or outdoors
-   **surface**: Text indicating game surface such as grass or turf
-   **game**: Contains @ home_team indicating who is hosting the matchup
- The following columns are entries that I have added to my dataset
-   **home_dvoa**: Contains the home team's average total DVOA for the 2024 season
-   **away_dvoa**: Contains the away team's average total DVOA for the 2024 season
-   **dvoa_diff**: Contains home_dvoa - away_dvoa
-   **home_rest_days**: Contains the number of days since the home team last played
-   **away_rest_days**:Contains the number of days since the away team last played
## Data Types:

-   **Column**: data type

-   **game_id**: object
-   **season**:  int64
-   **week**: int64
-   **away_team**: object
-   **home_team**: object
-   **away_score**: float64
-   **home_score**: float64
-   **gameday**: datetime64[ns]
-   **roof**: object
-   **surface**: object
-   **game**: object
-   **home_dvoa**: float64
-   **away_dvoa**: float64
-   **dvoa_diff**: float64
-   **home_rest_days**: Int64
-   **away_rest_days**: Int64



