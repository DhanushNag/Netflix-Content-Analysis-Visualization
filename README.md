# Netflix-Content-Analysis-Visualization

📌 Overview
This project uses Netflix's content dataset to perform a thorough exploratory data analysis (EDA). The dataset contains metadata about movies and TV shows available on Netflix, including type, country, cast, director, rating, genre, duration, and more.

We explore how content on the platform has evolved over time, which types of shows dominate, and who the most prolific creators and actors are.

🎯 Objectives
Clean and preprocess Netflix metadata

Analyze trends in content addition over the years

Compare distribution between Movies and TV Shows

Identify top genres, countries, ratings, actors, and directors

Visualize genre popularity across time

📊 Key Visualizations & Insights
Yearly Trend of Content Added

Line plot showing how many new titles were added each year.

Distribution of Content Types

Bar chart comparing the count of Movies vs TV Shows.

Top 10 Countries Producing Netflix Content

Horizontal bar chart displaying countries with the highest number of titles.

Most Common Content Ratings

Visual representation of the top 10 content rating categories.

Top 10 Most Frequent Genres

Bar plot of most commonly listed genres.

Distribution of Movie Durations

Histogram of movie lengths to understand typical runtime.

Top 10 Most Frequent Directors

Bar chart of directors with the highest number of titles.

Top 10 Most Frequent Actors

Actor appearances across all titles aggregated and visualized.

Genre Popularity Over Years

Exploded genre-year relationship to visualize top 5 genres by year.

🛠️ Tools and Technologies Used
Python 3.x

Jupyter Notebook

Pandas

Matplotlib

Seaborn

Counter (collections)

🧹 Data Preprocessing Steps
Standardized column names using str.lower() and str.replace()

Filled missing values for country, rating, cast, and director

Converted date_added to datetime format

Extracted year_added and month_added

Parsed duration for movies

Used string splitting and exploding for genre analysis

📦 How to Run the Notebook
Clone this repository or download the notebook.

Make sure netflix_titles.csv is in your working directory.

Install required libraries:


📌 Dataset Source
Netflix Titles Dataset - Kaggle

