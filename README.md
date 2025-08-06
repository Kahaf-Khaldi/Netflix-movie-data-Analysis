# Netflix-movie-data-Analysis
# Netflix Movie Data Analysis Project

A comprehensive data analysis project exploring movie trends, genres, popularity, and other key insights from a dataset of Netflix movies.  
This project demonstrates data cleaning, exploratory data analysis, and visualization using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.

## Project Overview

Netflix has transformed the entertainment industry through its data-driven strategies and global reach. Using a dataset of over 9,800 movies, this project answers important business questions about genre popularity, audience ratings, trends over time, and more.

### Key Questions Addressed

1. What is the most frequent genre of movies released on Netflix?
2. Which genre has the highest number of highly-voted movies?
3. What movie got the highest popularity, and what are its genres?
4. What movie got the lowest popularity, and what are its genres?
5. Which year features the most movies?

## Dataset

- **Rows:** 9,827 (after cleaning)
- **Columns:** 
    - Release_Date (year extracted)
    - Title
    - Popularity
    - Vote_Count
    - Vote_Average
    - Genre
- Initial dataset included additional columns such as Overview and Poster_Url, which were dropped for this analysis.

##  Data Cleaning & Preparation

- Handled NaN values & Duplicates: Ensured there were none in the dataset.
- Processed Release_Date: Extracted the year for temporal analysis.
- Split Genre Column: Movies with multiple genres were split into individual rows for each genre.
- Categorized Vote_Average: Divided into four categories (not_popular, below_avg, average, popular) based on quartiles.
- Dropped unused columns and formatted as needed for analysis.

## Exploratory Data Analysis

### 1. Most Frequent Genre

- **Drama** is the most common genre, appearing in over 14% of genre entries.

### 2. Genres with Highest Votes

- “Popular” votes make up over 25% of the dataset.
- Drama again leads, holding the majority share among high-vote movies.

### 3. Highest Popularity Movie

- **Movie:** *Spider-Man: No Way Home*
- **Genres:** Action, Adventure, Science Fiction

### 4. Lowest Popularity Movie(s)

- **Movies:** *The United States vs. Billie Holiday* and *Threads*
- **Genres:** Music, Drama, History, War, Science Fiction

### 5. Year with Most Movies

- **2020** witnessed the highest number of movie releases in the dataset.

## Visualizations

- Bar plots for genre distribution and vote categories
- Histogram showing movie release trends by year

## Technologies Used

- Python 3
- Pandas / NumPy for data processing
- Matplotlib / Seaborn for plotting

## Key Insights & Conclusion

- **Drama** is Netflix’s most produced genre.
- Most movies are scored as either "popular" or "not popular" with relatively balanced distribution.
- The peak year for releases was 2020.
- *Spider-Man: No Way Home* stands out in both popularity score and high ratings.

