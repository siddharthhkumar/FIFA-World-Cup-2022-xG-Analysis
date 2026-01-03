FIFA World Cup Final 2022 – xG & Finishing Analysis

This project analyzes the FIFA World Cup 2022 Final (Argentina vs France) using Expected Goals (xG) to evaluate team and player finishing efficiency.
The dashboard was built in Power BI, focusing on shot quality, goal conversion, and player performance.


Objectives

Compare Goals vs Expected Goals (xG) at team level

Measure finishing efficiency (Goals − xG)

Analyze player-level performance using shot-based metrics


Data Cleaning

Expanded nested event data (team, player, pass, shot)

Flattened semi-structured JSON into tabular format

Handled missing values and corrected data types

Filtered shot events for accurate xG calculations

Renamed technical fields for clarity

Challenges & Solutions

Nested data structure: Resolved using Power Query expansions

xG calculation errors: Fixed using DAX with event-level filters

Mixed aggregation levels: Standardized metrics to shot-level analysis

Visual inconsistencies: Corrected using appropriate table and matrix visuals


Dashboard Features

KPI cards (Goals, xG, Finishing Efficiency)

Team comparison (Argentina vs France)

Player performance table with conditional formatting

Interactive team slicer


Tools Used

Power BI

Power Query

DAX


Author

Siddharth Kumar
Aspiring Data Analyst | Sports Analytics Enthusiast
