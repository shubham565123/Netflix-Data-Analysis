# Netflix Data Analysis

## Problem Statement
Netflix, being a leading global media and video streaming platform with over 222 million subscribers worldwide, aims to leverage data-driven insights to make informed decisions on content production and business growth. The primary goal is to analyze the dataset containing information about movies and TV shows available on Netflix. The objective is to generate actionable insights that will guide Netflix in determining the types of shows and movies to produce and how to strategically expand its business in different countries.

## Table of Contents
1. [Basic Metrics](#basic-metrics)
2. [Data Preprocessing](#data-preprocessing)
3. [Analysis](#analysis)
    - [Total Number of Movies and TV Shows](#total-number)
    - [Distribution of Ratings](#distribution-ratings)
    - [Top Countries with Most Content](#top-countries)
    - [Production Over the Years](#production-over-years)
    - [Average Duration of Content](#average-duration)
    - [Top Genres](#top-genres)
    - [Best Time to Launch](#best-time-launch)
    - [Month-wise Analysis](#month-wise)

## Basic Metrics <a name="basic-metrics"></a>
- The dataset contains 8807 entries with 12 columns.
- Columns include show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, and description.

## Data Preprocessing <a name="data-preprocessing"></a>
- Converted 'date_added' to datetime format.
- Extracted numerical values from 'duration' column.
- Handled missing values in 'director', 'cast', 'country', and 'rating'.
- Dropped rows with missing values in 'date_added', 'duration', and 'rating'.

## Analysis <a name="analysis"></a>

### Total Number of Movies and TV Shows <a name="total-number"></a>
- Total Movies: 6126
- Total TV Shows: 2664

### Distribution of Ratings <a name="distribution-ratings"></a>
- TV-MA has the most content, while UR and NC-17 have the least.

### Top Countries with Most Content <a name="top-countries"></a>
#### Movies
1. United States: 2361
2. India: 927
3. Unknown Country: 439

#### TV Shows
1. United States: 841
2. Unknown Country: 390
3. United Kingdom: 245

### Production Over the Years <a name="production-over-years"></a>
- The popularity of TV show production increased after 2005.
- Most content was added in 2020 and 2019 for both movies and TV shows.

### Average Duration of Content <a name="average-duration"></a>
- Movies: 107.5 minutes
- TV Shows: 1.9 seasons

### Top Genres <a name="top-genres"></a>
- "International Movies" is the most popular genre, while "Classic & Cult TV" is the least popular.

### Best Time to Launch <a name="best-time-launch"></a>
- Top 5 weeks of the year when most movies are added on Netflix:
  1. Week 1
  2. Week 43
  3. Week 44
  4. Week 39
  5. Week 40

### Month-wise Analysis <a name="month-wise"></a>
- Best month to launch TV shows: December, followed by July and September.

This readme provides an overview of the Netflix Data Analysis project, including the problem statement, table of contents, and key findings from the analysis.
