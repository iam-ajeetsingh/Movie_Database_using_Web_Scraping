# Creating a Movie Database using Web Scraping

This project involves building a database of movie-related information by scraping data from [The Movie Database (TMDB)](https://www.themoviedb.org/). The project demonstrates the use of web scraping techniques, data extraction, and data analysis to create a structured dataset of movies, including their titles, ratings, genres, and cast details.

## Project Overview

The goal of this project is to:
- Scrape movie data from TMDB.
- Extract key information such as movie titles, user ratings, genres, and cast details.
- Store the extracted data in a structured format (e.g., CSV or Pandas DataFrame).
- Perform basic data analysis and visualization.

## Methodology

### Data Collection
- **Source**: [The Movie Database (TMDB)](https://www.themoviedb.org/)
- **Tools Used**:
  - `requests` library for sending HTTP requests.
  - `BeautifulSoup` library for parsing HTML content.
- **Process**:
  - Scraped the main movie listing page to extract movie titles, ratings, and URLs for individual movie pages.
  - Navigated to individual movie pages to extract additional details such as genres and cast information.

### Data Analysis
- **Libraries Used**:
  - `pandas` for data manipulation and storage.
  - `numpy` for numerical operations.
  - `matplotlib` and `seaborn` for data visualization.
- **Analysis Performed**:
  - Created a Pandas DataFrame containing movie titles, ratings, genres, and cast details.
  - Visualized the distribution of user ratings and other key metrics.

## Key Features

1. **Web Scraping**:
   - Extracted movie titles, user ratings, genres, and cast details using `BeautifulSoup`.
   - Implemented user-defined functions for modular and reusable scraping logic.

2. **Data Storage**:
   - Stored the scraped data in a Pandas DataFrame.
   - Exported the data to a CSV file for further analysis.

3. **Data Analysis**:
   - Analyzed the distribution of user ratings.
   - Identified popular genres and frequently appearing cast members.

4. **Error Handling**:
   - Implemented error handling for HTTP requests and missing data.
