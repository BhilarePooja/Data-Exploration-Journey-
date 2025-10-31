# Data-Exploration-Journey-
# 🎬 TMDB Movie Data Analysis

## Project Overview
This project explores and cleans the **Top 1000 Popular Movies dataset** from TMDB (The Movie Database).  
It focuses on understanding movie metadata, handling missing values, and performing exploratory data analysis (EDA).


## Objectives
- Load and explore the TMDB movie dataset.
- Identify and handle missing or inconsistent data.
- Clean and preprocess text and date features.
- Generate basic statistical summaries to understand dataset structure.


##  Dataset Description
The dataset includes details of 1000 popular movies with columns such as:

| Column Name | Description |
|--------------|-------------|
| `title` | Movie title |
| `release_date` | Official release date |
| `overview` | Short movie description |
| `tagline` | Promotional tagline |
| `production_companies` | Companies involved in movie production |
| `vote_average` | Average user rating |
| `vote_count` | Number of votes received |
| `popularity` | TMDB popularity score |


##  Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

##  Steps Performed
1. **Import Libraries** – Loaded required Python libraries.
2. **Load Dataset** – Read CSV file using `pandas.read_csv()`.
3. **Basic Data Exploration**
   - Viewed dataset shape and column info (`.info()`, `.head()`, `.describe()`).
4. **Missing Value Treatment**
   - Filled missing release dates manually for known movies.
   - Replaced missing text columns (`overview`, `tagline`, `production_companies`) with `"unknown"`.
5. **Statistical Summary**
   - Used `.describe()` and `.describe(include='all')` for numeric and categorical features.

##  Results & Insights
- Missing release dates were successfully filled for specific titles.
- Null text values were replaced with “unknown”.
- Dataset cleaned and ready for visualization or machine learning models.

# Open Jupyter Notebook
jupyter notebook "ML2 (3).ipynb"
