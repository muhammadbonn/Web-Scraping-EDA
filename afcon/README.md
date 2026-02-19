## African International Football Games Analysis

This project evaluates the historical performance of African national football teams (1872–2025) using a custom ranking system.
Instead of relying only on win/loss counts, the model:
- Applies weighted importance to different tournaments
- Adjusts scores based on competition stage
- Accounts for goal difference
- Converts match results into a structured performance score

The outcome is a data-driven ranking system that measures long-term competitive strength, trend evolution, and head-to-head dominance among African teams

Contents:
- [Methodology](#Methodology)
- [International football dataset](#International-football-dataset)
- [Selecting African Teams' Games from different tournaments](#Selecting-African-Teams'-Games-from-different-tournaments)
- [Define the stages of every game in the African Cup of Nations](#Define-the-stages-of-every-game-in-the-African-Cup-of-Nations)
- [Weight of every match based on tournament and stage](#Weight-of-every-match-based-on-tournament-and-stage)
- [From Match Results to Team Performance Metrics](#From-Match-Results-to-Team-Performance-Metrics)
- [Final Data and Ranking Teams](#Final-Data-and-Ranking-Teams)
- [Summary Plots](#Summary-Plots)
  - [Top Teams by Total Points](#Top-Teams-by-Total-Points)
  - [Goal Difference vs Total Points (Validate Logic)](#Goal-Difference-vs-Total-Points-(Validate-Logic))
  - [Win Percentage vs Ranking](#Win-Percentage-vs-Ranking)
  - [Goals For vs Goals Against (Offense vs Defense)](#Goals-For-vs-Goals-Against-(Offense-vs-Defense))
  - [Wins / Draws / Losses Distribution (Stacked Bar)](#Wins-/-Draws-/-Losses-Distribution-(Stacked-Bar))
- [Through Years](#Through-Years)
  - [Plots](#Through-Years-Plot)
- [Head-to-head](#Head-to-head)
  - [Result Samples](#Result-Samples)
  - [Egypt Head to Head Plot](#Egypt-Head-to-Head-Plot)
