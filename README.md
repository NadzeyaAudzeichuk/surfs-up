# Surfs-Up
Weather analysis using SQLite and SQLAlchemy.

# Overview

This project aims to analyze the weather dataset to determine if Surf n'Shake (a shop serving surfboards and ice cream) business is sustainable year-round. The focus will be on precipitations and temperatures for June and December. We will run an analysis in Jupyter Notebook. To connect the Oahu weather dataset (stored in SQLite database), we will use the SQLAlchemy library (to facilitate the communication between Python and the database).

## Results

We have precipitation data loaded into SQLite database. Using Python, Pandas functions and methods, and SQLAlchemy, we retrieve the temperatures for the months of June and December:

1. filter the date column of the Measurements table in the hawaii.sqlite database 
2. create DataFrames
3. generate the summary statistics for the given months.

Results are shown below:
![temps_stats_Jun_Dec.png](https://github.com/NadzeyaAudzeichuk/surfs-up/blob/main/Results/temp_stats_Jun_Dec.png)

## Summary
