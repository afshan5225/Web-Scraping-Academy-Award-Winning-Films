# Web Scraping Academy Award Winning Films

## Executive Summary

This project involves web scraping data on Academy Award-winning films from Wikipedia. The goal is to extract information about films, the year they won, the awards they received, and the number of nominations. The scraped data is then cleaned and organized into a structured DataFrame for analysis.

## Title

**Web Scraping Academy Award Winning Films**

## Problem Statement

The primary objective of this project is to gather and analyze data on films that have won Academy Awards. The data is sourced from the Wikipedia page listing Academy Award-winning films. This information is valuable for understanding trends in award-winning films, including their release years, the types of awards received, and their nomination counts.

## Methodology

1. **Data Collection**:
   - Utilized the `requests` library to fetch the content from the Wikipedia page.
   - Parsed the HTML content using `BeautifulSoup` to extract the relevant data from `<td>` tags.

2. **Data Cleaning**:
   - Used regular expressions (`re` library) to remove unwanted HTML tags and clean the data.
   - Addressed issues with inconsistent data patterns and missing values.

3. **Data Structuring**:
   - Organized the cleaned data into lists for films, years, awards, and nominations.
   - Created a DataFrame using `pandas` to structure the data for further analysis.

4. **Data Analysis**:
   - Converted data types for numerical columns to integers.
   - Checked for and addressed any missing values.

## Skills

- **Python Programming**: Utilized Python for scripting and data manipulation.
- **Web Scraping**: Experienced with `requests` and `BeautifulSoup` for data extraction.
- **Data Cleaning**: Applied regular expressions for text cleaning and data preparation.
- **Data Analysis**: Used `pandas` for data structuring, type conversion, and basic analysis.


