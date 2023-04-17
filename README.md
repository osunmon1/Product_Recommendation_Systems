Olist Recommendation Systems Capstone Project 
=======
#### Author: Olabisi Sunmon | 10th April 2023

#### Problem Statement;


How can we create a customised product recommendation system using data analysis and machine learning techniques to help Olist customers discover new products and find relevant items for purchase, to boost revenue and customer purchase rates.

-----------
The models trained were:
- Market Basket Analysis
- FunkSVD
- KNNWithMeans
- NormalPredictor
- CoClustering


Project Organization
------------

notebooks
---------
- `1)1_data_collection.ipynb` - Imported the unprocessed dataset from the origin and performed data cleansing where appropriate.
- `2_eda.ipynb`-Performed exploratory data analysis in order to gain valuable insights from the data.
- `3_modelling_comparing_market_basket.ipynb` - Exploring different granularities using Market Basket
- `4_ modelling _comparing_techniques.ipynb` - Exploring different collaborative filtering techniques


reports 
--------
- Capstone_report.pdf - A report detailing the process, key insights, and results of my project 


src
------
- data - folder containing data
  - Raw -folder containing raw data (9 .csv files)
  - Clean - folder containing cleaning data (9 .pkl files)
  - Processed - folder containing processed data (3 .pkl files)

-----
- requirements.txt - commands to recreate the enviroment needed to run the notebooks# Product_Recommendation_Systems
