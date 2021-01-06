# Boardgamegeek
Ranking of boardgamegeek dataset

The aim of this project is to rank BGG games using different criteria: average and Bayesian average.

Two Jupyter notebooks were created:

1- BGG Rank API

2- ItemRank

The first notebook downloads the official BGG rank from BGG website. These data will then be used to evaluate how close the calculated ranks are with respect to the official one.

The second notebook contains the ItemRank class that could be used to calculate rating average and Bayesian average and creates a rank for a given Pandas Dataframe.
The rank_comparison function instead compares two ranks using various rank comparison techniques and provides some graphs
