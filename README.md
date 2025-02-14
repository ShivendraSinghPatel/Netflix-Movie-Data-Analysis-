# Netflix Movie Data Analysis

## Overview
This project analyzes a Netflix movie dataset using Python and various data analysis libraries. The goal is to extract meaningful insights about Netflix's movie collection, such as the most frequent genres, trends in movie releases, and rating distributions.

## Dataset Summary
- The dataset consists of **9,827 rows and 9 columns**.
- No missing or duplicate values were found.
- Some columns were **cleaned** or **removed** to enhance analysis accuracy.
- The dataset includes **genres, release dates, popularity scores, and vote averages**.

## Data Preprocessing
Several preprocessing steps were performed to clean and prepare the data:
1. **Converted the `Released_Date` column** to a proper datetime format and extracted only the year.
2. **Dropped unnecessary columns**: `Overview`, `Original Language`, and `Poster URL`.
3. **Handled outliers** in the `Popularity` column.
4. **Categorized `Vote_Average`** for better interpretation.
5. **Cleaned `Genre` values**, handling comma-separated entries and whitespace issues.

## Data Analysis and Insights
Key questions explored in the analysis:
1. **What is the most frequent genre of movies released on Netflix?**
2. **How has the number of movie releases changed over the years?**
3. **What is the distribution of movie ratings on Netflix?**
4. **Are there any trends in popularity scores over time?**

## Technologies Used
The project utilizes the following Python libraries:
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Seaborn & Matplotlib** – Data visualization

## Visualizations & Results
The notebook includes various visualizations, such as:
- **Bar charts** showing the most common movie genres.
- **Line graphs** depicting trends in movie releases over time.
- **Histograms** displaying the distribution of ratings.

## Future Enhancements
- Include **machine learning models** to predict movie popularity.
- Expand analysis to include **Netflix TV shows**.
- Compare Netflix data with other streaming platforms.

## Contributors
- **Shivendra Singh**  
 Follow Me -  [LinkedIn](https://www.linkedin.com/in/shivendraspatel/)  


