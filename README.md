# Collaborative Filtering Recommendation System

A Python-based movie recommendation system that implements both user-based and item-based collaborative filtering algorithms using the MovieLens 100K dataset.

## Project Overview

This project implements a Collaborative Filtering-based Recommendation System that suggests movies to users based on their past interactions and preferences, as well as those of similar users. The system is built on the assumption that users with similar behaviors and preferences will enjoy similar items.

### Key Features

- Data preprocessing and exploration of the MovieLens 100K dataset
- Implementation of User-Based Collaborative Filtering
- Implementation of Item-Based Collaborative Filtering
- Model evaluation using RMSE and precision/recall metrics
- Top-N movie recommendation generation for users
- Optional visualization of user similarities and recommendation performance

## Dataset

The project uses the MovieLens 100K dataset, which contains 100,000 ratings from 943 users on 1,682 movies. The dataset can be downloaded from:
[https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset)



## Project Structure

```
collaborative-filtering-recommender/
│
├── README.md                   # Project description and instructions
├── requirements.txt            # Python dependencies
│
├── data/                       # Dataset directory
│   ├── u.data                  # Rating data
│   ├── u.item                  # Movie information
│   └── u.user                  # User information
│
├── notebooks/                  # Jupyter notebooks
│   ├── 01_data_preprocessing.ipynb          # Data loading and preparation
│   ├── 02_user_based_cf.ipynb               # User-based collaborative filtering
│   ├── 03_item_based_cf.ipynb               # Item-based collaborative filtering
│   └── 04_evaluation_and_visualization.ipynb # Model evaluation and plots
│
├── src/                        # Source code
│   ├── __init__.py             # Package initialization
│   ├── data_loader.py          # Functions to load and preprocess data
│   ├── recommender.py          # Core collaborative filtering algorithms
│   └── evaluation.py           # RMSE, precision, recall computation functions
│
└── results/                    # Output directory
    ├── top_n_recommendations.csv  # Generated recommendations
    └── evaluation_metrics.json    # Performance metrics
```










This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- The MovieLens dataset is provided by GroupLens Research
- This project is for educational purposes
