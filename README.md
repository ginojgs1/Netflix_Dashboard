
# Netflix_Dashboard

### Dashboard Link : https://app.powerbi.com/reportEmbed?reportId=ef5c45a3-b965-4150-8c2b-7324bcee9f13&autoAuth=true&ctid=7a95ad65-55ee-41e3-ba46-acbdf605ee3d

## Problem Statement

 1. Data Cleaning & Preparation
a. Load and inspect the data
- Load both Credits and Title tables.
- Check for missing values, inconsistencies, and duplicates.
- Ensure correct data types (e.g., numerical, categorical, date).
b. Handle missing or inconsistent values
- Drop or impute missing imdb_score, tmdb_score, or other key fields.
- Normalize inconsistent genres or role entries (e.g., capitalization, typos).
c. Merge datasets
- Use the shared Id field (Team Id) to merge Credits and Title tables into a unified dataset.

2. Data Transformation
a. Create useful features
- Convert release_year to movie_age (e.g., 2025 - release_year).
- Create a binary flag for high ratings (e.g., imdb_score > 7.5).
b. One-hot encode categorical data
- Fields like genres, type, age_certification, and production_countries.
c. Group-based insights
- Group by role to see which teams contribute to higher-rated content.
- Group by genres or production_countries to assess performance by category or region.

3. Exploratory Data Analysis (EDA)
a. Descriptive statistics
- Summary stats on runtime, scores, votes, popularity.
b. Visualizations
- Bar charts: Top 10 genres, average scores by certification.
- Box plots: Score distributions across roles or certifications.
- Scatter plots: TMDB vs IMDb score relationships.
c. Correlation analysis
- Which variables (votes, runtime, popularity) correlate with IMDb/TMDB scores?

4. Insights You Could Extract
- What roles (director, actor, writer) most influence high-rated content.
- Genres with consistently high/low ratings.
- Relationship between runtime and viewer ratings.
- Whether certain countries produce more highly rated or popular content.
- Discrepancies between IMDb and TMDB ratings.



### Task 

1.Connect and get data from anExcelfile named “1910_m4_assign_dataset_v1.0”. 

2.Open the power query editor and perform the data cleaning task.

3.Open the data model and make relationshipsamong all tables.

4.Create measures for “total content” and“Runtime hours” formulas using DAX.


![Image](https://github.com/user-attachments/assets/8910106b-e690-49eb-97e8-cc6d2b679d38)

        
5.Show bar plot for most available content for top 5 genresby type.

6.Show line chart for a count of released content by each year by their type.

7.Show production country and run time for each content on the map.

8.show the total distribution of content typesusing the donut chart.

9.Create cards for the total runtime, the total count ofmovies andtv shows, and the average rating of IMDB.

10.Add slicer for genres, release year, and title.

11.Add the Netflix logo and a little introduction toNetflix(use text box).

Note: sample of dashboard.


![Image](https://github.com/user-attachments/assets/a2118704-f405-4309-a989-40d263f26ac4)

        
