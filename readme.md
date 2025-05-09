# Netflix Data Analysis and Visualization

## Project Overview
This project explores the Netflix dataset, performs data cleaning and preprocessing, and provides various analyses and visualizations to uncover trends in the Netflix content library. The analysis includes identifying the distribution of content types (movies vs. TV shows), exploring popular genres, and analyzing content release patterns by country and year.

## Data
The dataset used for this analysis is from Netflix, which contains information about movies and TV shows, including their release year, type (movie or TV show), genre, country of production, and more.

## Steps Taken in the Analysis
1. **Data Preprocessing**:
   - Converted columns like `date_added` to datetime objects.
   - Created new columns for year and month when the content was added.
   - Split genres and processed durations for better analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed the distribution of Movies vs. TV Shows.
   - Identified the most popular genres and countries producing Netflix content.
   - Examined trends over time regarding content releases.

3. **Data Visualizations**:
   - Created various visualizations using **Matplotlib** and **Seaborn** to represent the insights, such as:
     - Distribution of content (Movies vs TV Shows).
     - Trends in content added per year.
     - Top 10 content-producing countries.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas** (for data manipulation)
- **Matplotlib & Seaborn** (for data visualization)

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/akbarnaeem/netflix-data-analysis.git
