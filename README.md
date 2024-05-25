Preseason Rankings Affecting March Madness Results

Overview
This GitHub repository contains the datasets, scripts, and outputs from my project analyzing how preseason rankings correlate with the success of teams in the NCAA March Madness basketball tournament. The goal is to explore if teams with higher preseason rankings generally perform better in the tournament compared to lower-ranked teams.

Hypothesis
The hypothesis under investigation is that higher preseason rankings are positively correlated with deeper runs in the NCAA March Madness tournament, indicating a predictive value of these rankings on tournament outcomes.

Data Source
The primary dataset used for this analysis is provided in the CSV file named "CBB Preseason Rankings.csv". This file includes detailed records from various NCAA seasons, featuring the following columns:

Year: The NCAA tournament year.
Rank: Preseason ranking of the team.
Team: Name of the college basketball team.
Round: Final round achieved in the tournament.
The data covers multiple years and provides a comprehensive view of the preseason expectations versus actual tournament performance.

Analysis Techniques
Analysis of the data involved several key steps:

Data Cleaning: Standardizing team names and handling any missing or incorrect data entries.
Statistical Analysis: Using correlation coefficients to quantify the relationship between preseason rankings and tournament outcomes.
Visualization: Creating plots with ggplot2 to visually represent trends and insights, such as the frequency of top-ranked teams reaching various tournament stages.

Key Findings
Teams with higher preseason rankings tend to perform better in the NCAA tournament, suggesting that these rankings are a good predictor of tournament success.
Visualizations indicate a clear trend where higher-ranked teams reach later rounds more consistently than their lower-ranked counterparts.
