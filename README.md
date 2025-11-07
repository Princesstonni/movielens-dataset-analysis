

# 🎬 MovieLens Dataset Analysis

## Table of Contents
1. [Executive Summary](#executive-summary)  
2. [Introduction](#1-introduction)  
3. [Dataset Overview](#2-dataset-overview)  
4. [Python Analysis](#3-python-analysis)  
5. [Key Metrics and Visualizations](#4-key-metrics-and-visualizations)  
6. [Visualizations and Dashboard](#5-visualizations-and-dashboard)  
7. [Insights and Findings](#6-insights-and-findings)  
8. [Dataset Instructions](#7-dataset-instructions)  
9. [Conclusion](#8-conclusion)  
10. [Project Files](#9-project-files)  

---

## Executive Summary
This project presents a comprehensive analysis of the MovieLens dataset using Python for data exploration, cleaning, and visualization. The primary objective was to examine user rating behavior, genre patterns, and movie performance, uncovering actionable insights and trends that can inform content recommendation strategies.

**Prepared by:** Osolake Mariam Omotolani  
---

## 1. Introduction
The MovieLens dataset provides extensive information on user-movie interactions, including ratings, genres, and timestamps. This project leverages Python to process and analyze the data, aiming to:

- Identify user preferences and rating behavior  
- Explore genre popularity and distribution  
- Highlight high-performing movies  
- Examine patterns across users and categories  

By combining programmatic analysis with Python visualizations, the project demonstrates the value of transforming raw data into actionable insights.

---

## 2. Dataset Overview
The dataset comprises three main components: users, movies, and ratings. Key fields include:

- **userId**: Unique identifier for each user  
- **movieId**: Unique identifier for each movie  
- **rating**: Score given by a user (scale: 0.5 – 5.0)  
- **timestamp**: Date and time the rating was submitted  
- **genre**: Category or categories associated with each movie (e.g., Drama, Comedy, Action)  

This dataset allows for multi-dimensional analysis, such as ratings per genre, user engagement levels, and the relationship between movie popularity and ratings.

---

## 3. Python Analysis
Python was used to perform data preprocessing, analysis, and visualization. Key steps included:

1. **Data Cleaning** – Handling missing values, duplicates, and ensuring data consistency.  
2. **Exploratory Data Analysis (EDA)** – Calculating descriptive statistics, identifying trends, and summarizing rating distributions.  
3. **Aggregation and Grouping** – Computing average ratings per movie, total ratings per genre, and unique users per category.  
4. **Top Performing Movies** – Identifying the top 5 highest-rated movies based on average rating and rating count.  
5. **User Engagement Analysis** – Examining how users interact with different genres and movies, including rating frequency and distribution patterns.  

This structured approach ensures meaningful insights are extracted efficiently.

---

## 4. Key Metrics and Visualizations
To highlight trends and patterns, Python-generated visualizations were created, including:

- **Rating Distribution** – Histogram showing frequency of ratings across all movies  
- **Genre Count** – Bar chart representing the number of movies per genre  
- **Average Rating by Release Year** – Line chart showing trends in ratings over time  
- **Top 5 Highest-Rated Movies** – Bar chart of highest-rated movies  
- **User Rating Behavior** – Distribution of ratings submitted per user  
- **Overall Rating Spread** – Comprehensive view of rating frequency across all movies  

---

## 5. Visualizations and Dashboard

The Python-generated visualizations provide insights into user rating behavior, genre popularity, and movie performance. Each chart highlights a key aspect of the MovieLens dataset analysis.

<p align="center">
  <img src="Distribution of Rating.png" alt="Rating Distribution" width="300">
  <img src="Number of Genres.png" alt="Genre Count" width="300">
</p>

<p align="center">
  <img src="Average Ratings.png" alt="Average Rating by Year" width="300">
  <img src="Average Movie Rating.png" alt="Top 5 Highest-Rated Movies" width="300">
</p>

<p align="center">
  <img src="Distribution of Rating per Movie.png" alt="User Rating Behavior" width="300">
  <img src="Distribution Rate.png" alt="Overall Rating Spread" width="300">
</p>

---

## 6. Insights and Findings
The analysis revealed several key insights:

- **Rating Trends** – Most ratings are concentrated between 3.0 and 4.0, suggesting moderate satisfaction among users.  
- **Genre Popularity** – Drama and Comedy dominate user engagement, while niche genres receive fewer ratings.  
- **High-Performing Movies** – A small subset of movies consistently achieves high average ratings, indicating strong user approval.  
- **User Engagement Patterns** – Users tend to rate selectively, showing preference for certain genres over others, rather than distributing ratings evenly.  
- **Potential Recommendations** – Insights suggest opportunities for personalized recommendations and identifying under-rated movies with high potential.

---

## 7. Dataset Instructions

> **Note:** The original MovieLens dataset used in this analysis **is not publicly available** and cannot be shared due to privacy and licensing restrictions.  

To ensure reproducibility of this project, a **small sample dataset** is provided in the `data/` folder. This sample contains the same structure as the full dataset (`userId`, `movieId`, `rating`, `timestamp`, `genre`) and allows the notebook to run and generate all visualizations.  

**How to use the sample dataset:**  
1. Ensure the sample dataset file (`sample_movielens.csv`) is placed in the `data/` folder of the repository.  
2. In the notebook, the code automatically loads the sample dataset:
   import pandas as pd
df = pd.read_csv('data/sample_movielens.csv')
3. All analysis, charts, and insights will run normally using this sample dataset.  
4. If you have access to the full MovieLens dataset, you can replace the sample dataset file with the full dataset (ensuring the same column structure) to perform the complete analysis.

---

## 8. Conclusion

The MovieLens dataset provides rich insight into user preferences, genre trends, and movie performance. By combining Python-based analysis with visualizations, this project demonstrates how structured data exploration can:

- Reveal actionable insights for decision-making  
- Support personalized movie recommendation strategies  
- Highlight user behavior patterns and engagement opportunities  

Overall, this project emphasizes the importance of integrating data analysis with visualization to transform raw data into meaningful knowledge.

---

## 9. Project Files

The following project files are included in the repository:

- **MovieLens Analysis Report (`.md` / `.pdf`)** – Comprehensive documentation of the analysis, including objectives, dataset overview, Python analysis, visualizations, insights, and conclusions.  
- **Jupyter Notebook (`.ipynb`)** – Python scripts for data cleaning, analysis, and visualizations.  
- **Sample Dataset (`sample_movielens.csv`)** – Minimal data for demonstration purposes.  


