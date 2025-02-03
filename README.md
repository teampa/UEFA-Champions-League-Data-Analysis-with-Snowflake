# UEFA-Champions-League-Data-Analysis-with-Snowflake

This repository contains SQL queries and insights from analyzing UEFA Champions League data (2020-2023) using Snowflake.

## Project Overview
- **Goal:** Extract key insights from structured soccer data to support sports analytics and team performance evaluation.
- **Key Metrics Analyzed:**
  - Top 3 home-scoring teams.
  - Team possession dominance in matches.
  - Teams winning duels but losing games.

## Dataset
- **Schema Name:** SOCCER
- **Tables:** `TBL_UEFA_2020`, `TBL_UEFA_2021`, `TBL_UEFA_2022`
- Columns include team names, scores, possession percentages, duels won, and predictions.

## Queries
- SQL queries are stored in the `/queries` folder. Each query focuses on specific metrics:
  - Top 3 teams with the highest home scores: `top_home_scoring_teams.sql`
  - Team possession dominance: `possession_dominance.sql`
  - Teams winning duels but losing matches: `duels_won_but_lost.sql`
