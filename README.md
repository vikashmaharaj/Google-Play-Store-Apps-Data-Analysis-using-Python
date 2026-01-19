# Google-Play-Store-Apps-Data-Analysis-using-Python

This project performs exploratory data analysis (EDA) on the Google Play Store Apps dataset using Python and Pandas. The goal of this project is to understand app trends, ratings, reviews, categories, and installation patterns present in the Play Store.

## Dataset
The dataset used in this project is taken from Kaggle:
https://www.kaggle.com/datasets/lava18/google-play-store-apps

## What This Project Does

- Loads and explores the Google Play Store dataset using Pandas
- Displays basic structure of the dataset using head, tail, info, and describe
- Checks dataset shape, column names, and missing values
- Searches apps by name using string filtering
- Calculates average app ratings
- Analyzes unique app categories and category-wise counts
- Finds average ratings per category
- Counts the number of apps with a perfect rating (5.0)
- Cleans the `Reviews` column and converts it into numeric format
- Identifies apps with the highest number of reviews
- Compares average ratings between Free and Paid apps
- Cleans the `Installs` column by removing special characters
- Converts installs into integer format
- Identifies the top apps based on highest installation counts

## Technologies Used

- Python
- Pandas
- Jupyter Notebook / Google Colab

## Outcome

This analysis helps in understanding:
- Which categories perform better based on ratings
- Which apps have the highest engagement through reviews
- Differences between Free and Paid apps
- Most installed apps on the Play Store

## Author

Anjali
