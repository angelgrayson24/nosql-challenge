# nosql-challenge
You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.
# Eat Safe, Love Project

## Overview
Eat Safe, Love is a project that involves evaluating food establishments in the United Kingdom based on the ratings provided by the Food Standards Agency (FSA). This project uses MongoDB as the database to store and manage the establishments' data. The goal is to assist journalists and food critics in deciding where to focus future articles based on hygiene ratings.

## Project Structure

### `data`
- Contains the establishments.json file, which includes information about various food establishments in the UK.

### `scripts`
- `mongo_import.py`: Python script to import data from establishments.json into MongoDB.

### `analysis`
- `food_analysis.py`: Python script to perform data analysis on the establishments in MongoDB, including filtering, updating values, and exploratory analysis.
# Analysis and Usage
# MongoDB Database
The data from establishments.json is imported into a MongoDB database named eat_safe_love.
# Data Analysis
Use the food_analysis.py script to perform various analyses on the data. Examples include filtering establishments, updating values, and exploratory analysis.
## Jupyter Notebook (Optional)
Explore the data interactively using Jupyter Notebook. Open the food_analysis.ipynb file for a guided analysis.
