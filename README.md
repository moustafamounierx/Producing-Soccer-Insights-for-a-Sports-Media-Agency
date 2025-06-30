1. TEAM_HOME_WITH_MOST_GOALS.sql
Goal: Identify the top 3 teams that scored the most goals at home in the 2020–21 UEFA Champions League.
Method: Sum TEAM_HOME_SCORE grouped by TEAM_NAME_HOME, sort in descending order, and limit to 3 results.
https://www.datacamp.com/datalab/w/d402fe17-7cf3-439b-876b-0c2ec5d37981/edit#97447e46-5294-4a2f-af1c-9fbc875d3622

3. TEAM_WITH_MAJORITY_POSSESSION.sql
Goal: Find the team that had majority possession (home or away) in the most games during the 2021–22 season.
Method: Use UNION ALL to count majority possessions from both sides, then group and rank.
https://www.datacamp.com/datalab/w/d402fe17-7cf3-439b-876b-0c2ec5d37981/edit#69d80798-e101-4c36-901b-2ae6f0255f95

5. TEAM_WON_DUEL_LOST_GAME_STAGE_WISE.sql
Goal: For each stage, list teams that won more duels but still lost the match in the 2022–23 season.
Method: Filter rows where duels were won but match was lost, combine both home and away cases with UNION ALL, and return STAGE + TEAM_LOST.
https://www.datacamp.com/datalab/w/d402fe17-7cf3-439b-876b-0c2ec5d37981/edit#4534efcd-5b4f-409c-a7aa-29b85616c96b
