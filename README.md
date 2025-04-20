# Netflix Data Analysis Project

This project focuses on analyzing the Netflix dataset using Python (Pandas, Matplotlib/Seaborn) to uncover patterns in content trends, genres, release years, and other key insights.

## Overview

- *Objective:* To perform EDA (Exploratory Data Analysis) on Netflix's publicly available dataset and gain meaningful insights using visualizations and data cleaning techniques.
- *Dataset Source:* [Kaggle Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- *Tools Used:* Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

## Key Tasks Performed

1. *Data Cleaning*
   - Removed nulls in critical columns like director, cast, country, and date_added
   - Converted date_added to datetime format
   - Dropped rows with invalid or unknown values
   - Ensured correct datatypes

2. *Visualizations*
   - Top 10 genres on Netflix
   - Top 10 directors (excluding unknowns)
   - Top 10 countries by content count
   - Release year distribution
   - Content added over time
   - Content type count (Movies vs TV Shows)
   - Genre-wise content breakdown (stacked bar)

## How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/MRoshaan/Netflix-Content-Analysis.git
