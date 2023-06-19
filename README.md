# Yelp Restaurant Recommendation System

## 1. Introduction


Yelp Inc. is an American company that develops the Yelp.com website and the Yelp mobile app, which publish crowd-sourced reviews about businesses. It also operates Yelp Guest Manager, a table reservation service. It is headquartered in San Francisco, California.Yelp was founded in 2004 by former PayPal employees Russel Simmons and Jeremy Stoppelman. Yelp grew in usage and raised several rounds of funding in the following years.Today, the website and their mobile application publish crowd-sourced reviews about local businesses as well as certain metadata about them that can help in customer's **decision-making process**.Yelp uses automated software to recommend the **most helpful** and **reliable reviews** for the Yelp community from such a large and diverse dataset.

This dataset is a subset of Yelp's businesses, reviews, and user data. It was originally put together for the Yelp Dataset Challenge which is a chance for students to conduct research or analysis on Yelp's data and share their discoveries. In the most recent dataset you'll find information about businesses across 8 metropolitan areas in the USA and Canada.


## 2. Objective


In this case study, I've implemented three types of recommendation systems: 
- **Knowledge/Rank Based recommendation system**
- **Similarity-Based Collaborative filtering**
- **Matrix Factorization Based Collaborative Filtering**
- **Clustering-based recommendation system**
- **Content-based collaborative filtering**

## 3. Dataset


Out of many attributes available in the yelp_reviews data, we will only use the following four attributes:
- business_id
- business_name
- stars
- user_id
- text: The text review by the user

## 3. Setup

- The environment used is Jupyter Notebook.
- Run the data_files_preparation.ipynb to download the data files from Kaggle and store it into sqlite databse
- Install surprise using the command --conda install -c conda-forge scikit-surprise
- Run the yelp_recommendation_content_based.ipynb and yelp_recommendation_colaborative_filtering.ipynb
