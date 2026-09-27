# fifa19-player-statistic-analytic

## Overview

This project analyses the FIFA 19 player dataset containing 18,147 professional football players. The analysis explores player ratings, age, preferred foot, skill moves, playing positions, player attributes, market value, and wages.

## Objectives

The project investigates:

- Whether left-footed and right-footed players differ in Overall rating.
- Whether forwards score higher than defenders.
- Whether Overall ratings differ across goalkeeper, defender, midfielder, and forward groups.
- Which player attributes are most strongly associated with Overall rating.
- How Age is related to Potential.
- Whether preferred foot and skill tier are related to position group.

## Analysis Included

- Data cleaning and feature preparation.
- Exploratory data analysis.
- Group summaries using means and standard deviations.
- Histograms and boxplots.
- Age versus Overall scatter plots with a trend line.
- Position-group bar charts with error bars.
- Shapiro-Wilk normality tests.
- Q-Q plots.
- Mann-Whitney U tests.
- Kruskal-Wallis tests.
- Tukey post-hoc comparisons.
- Pearson and Spearman correlation analysis.
- Correlation heatmaps.
- Chi-Square tests for categorical relationships.
- Stacked bar charts.
- A final scouting-team summary.

## Main Findings

- Left-footed players had a slightly higher average Overall rating than right-footed players.
- Midfielders had the highest average Overall rating.
- Goalkeepers differed significantly from the outfield position groups in Overall rating.
- BallControl had the strongest tested positive relationship with Overall rating, with a correlation of approximately 0.46.
- Potential decreased as Age increased.
- Preferred foot and position group were related.
- Skill tier and position group were analysed using a Chi-Square test.

## Tools and Libraries

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses FIFA 19 player statistics sourced from the EA Sports/Kaggle FIFA 19 Complete Player Dataset.

## Important Note

The findings describe statistical associations in the dataset. They do not prove that one variable causes another.
