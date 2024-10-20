# Netflix Report

## Table of Content
- [Project Overview](#project-overview)
- [Data Source(s)](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Explanatory Data Analysis](#explanatory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendations](#recommendation)
- [Limitations](#limitation)
- [References](#references)

## Project overview
This data analysis project aims to provide insight into the Netflix world over the years. This is done by analyzing various aspects of the company's uploads, genres and most watched movies or shows. In so doing, the primary objective, hence is to identify the most watched and liked geners and shows; the ratings and release date (year).

### Data Source(s):
- Netflix Data: The primary dataset used for this project is the "netflix_title.csv" file, containing detailed information about each upload from the company.

![Screenshot 2024-10-19 221946](https://github.com/user-attachments/assets/04eadbc3-58f4-4d89-aeed-b8656a414671)
![Screenshot 2024-10-19 223352](https://github.com/user-attachments/assets/ccd3e410-4d16-4bbd-b054-806811ba9a39)


### Tool(s):
- Excel - For data cleaning and formatting. [Download here](https://github.com/user-attachments/files/17447407/netflix_titles.csv)
- SQL Server - Data Analysis.
- Power BI - Creating reports.

### Data Cleaning/Preparation

#### Data cleaning involves several key steps:
- Removing Duplicates: Identify and remove any duplicate entries to ensure accurate analysis.
- Handling Missing Values: Analyze missing data and determine appropriate strategies (e.g., imputation or removal) to maintain data integrity.
- Standardizing Formats: Ensure consistent formatting for key fields, such as dates and categorical variables.
- Data Type Conversion: Convert data types where necessary (e.g., changing string representations of numbers to integers).

### Explanatory Data Analysis
#### In this phase, we:
- Explore Data Distribution: Use descriptive statistics to summarize key variables such as release years, ratings, and genre distributions.
- Visualize Trends: Create initial visualizations to identify patterns in the data, such as genre popularity over time.
- Assess Correlations: Investigate relationships between ratings and viewership metrics to inform subsequent analysis.

### Data Analysis
#### The analysis will focus on:
- Genre Popularity: Utilize SQL queries to aggregate viewership data by genre, examining which genres have the highest engagement.
- Top Titles: Identify the most-watched movies and shows, along with their average ratings.
- Temporal Trends: Analyze how the number of uploads and viewership figures have evolved over the years, looking for significant changes in consumer preferences.
- Comparative Analysis: Compare genres and titles against each other to derive insights into competitive performance.

### Results/Findings
- Most-Watched Genres: Summary of the top three most-watched genres based on viewership data.
- Top Titles/Genres: A list of the top ten shows and movies along with their ratings.
- Trends Over Time: Visualization of trends in genre popularity and upload rates from year to year.
- Key Insights: Any noteworthy patterns or correlations discovered during the analysis.

### Recommendations
- Content Strategy: Suggest genres that Netflix should focus on based on viewer preferences and trends.
- Targeted Marketing: Recommend marketing strategies tailored to the most popular titles and genres.
- Improving Ratings: Propose ways to enhance the quality of content in underperforming genres.

### Limitations
- Data Completeness: Some data may be missing or incomplete, which can affect the accuracy of insights.
- Temporal Constraints: The analysis is limited to the dataset's time frame, which may not capture recent trends.
- Causation vs. Correlation: Findings may indicate relationships but do not necessarily imply causation.

### References
- Excel
- MySQL
- Power BI
- [Netflix_database.csv](http://netflix.com)
