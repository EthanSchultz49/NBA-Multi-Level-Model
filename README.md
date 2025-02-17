# NBA-Multi-Level-Model
Looking Past the Box Score: A Multilevel Modeling Exploration of VORP Variations in NBA Players

In this project, we explore the variations in VORP (Value Over Replacement Player) among NBA players, utilizing a multilevel modeling approach to predict VORP based on factors not directly included in its calculation. VORP evaluates a player's performance relative to an "average" player at their position. By leveraging variables like points per game, salary, age, years in college, and draft status, we aim to develop a model that can assist NBA general managers in evaluating player performance beyond traditional statistics, particularly for roster decisions.

Our analysis involves data sourced from Basketball Reference, with the goal of identifying key predictors for VORP and modeling its variability across seasons. We implement multilevel models using maximum likelihood and restricted maximum likelihood estimations, incorporating both fixed and random effects. After cleaning and processing the data for 21 players over multiple seasons, we assess the influence of both level 1 (seasonal) and level 2 (career) variables on VORP.

Key findings include:

Points per game (cenPTS) is a strong predictor of VORP at the seasonal level, showing a positive relationship.
Years spent in college negatively impacts VORP, suggesting that players with less college experience may have a higher VORP.
The final model with random slopes reveals that VORP variability between seasons is best explained when accounting for individual player differences in how points per game influence VORP.
The results of this project underscore the complexity of player evaluation in basketball, highlighting the value of incorporating both statistical modeling and player-specific factors in decision-making processes.
