﻿# UCSD DSE: Building Recommender Systems for Video Games on Steam

![Valve Steam logo](valve-steam.jpg)

This project is to construct a recommender system using users and games data on Steam. The project uses the Bayesian Personalized Ranking algorithm to develop its collaborative filtering model.
The main objective is to accurately capture user preferences and analyze strengths and weaknesses of our model to build a more complete understanding of the data and the video game industry as a whole.

### Project structures

| directory | description |
| ------ | ------ |
| archive | - preliminary analysis using tensorflow <br> - item-item recommendations analysis |
| dashboard | - Tableau dashboard <br> - jupyter notebook to process model output data to build a dashboard <br> - dashboard images  |
| lib | - cookbook library <br> - data processing utility scripts |
| notebooks |  This includes jupyter notebooks for <br> - collaborative filtering model analysis <br> - hyperparameters search for collaborative filtering model <br> - cold start problem analysis with collaborative filtering model <br> - hybrid model analysis |
| notebooks/pca | - jupyter notebooks for principal component analysis <br> - pca plot images |
| outputs | the final model output data of the top 20 game recommendations for user and item |
| poster | project poster |
| report | project final report |


Link to raw data here: https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data

To run model:
1) Fix raw data files using ./lib/fix_raw_data.py.
2) Run data preprocessing notebook in notebooks.
3) Run hyperparameter search notebook to find optimal hyperparameters for model.
4) Run analysis notebooks.

To be done:
Convert notebooks to py files.
