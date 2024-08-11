# Zomato Case Study: Geospatial & N-gram Analysis


### Table of Contents
 - [Project Overview](Project-Overview)
 - [Data Sources](Data-Sources)
 - [Data Extraction/Cleaning](Data-Extraction/Cleaning)
 - [Exploratory Data Analysis](Exploratory-Data-Analysis)
 - [Results](Results)
 - [Limitations](Limitations)
 - [Tools and Libraries](Tools-and-Libraries)


### Project Overview

This project combines geospatial analysis with unigram, bigram, and trigram analysis to uncover insights from restaurant data on Zomato. The analysis aims to understand restaurant distribution, customer preferences, and key trends in the food industry

### Data Sources

- Python -Jupyter notebook
- sqlite 

### Data Extraction/Cleaning

1. Extracted data from 'zomato_rawdata.sqlite' file using pandas library
2. Handle missing or duplicate data.

### Exploratory Data Analysis

EDA involves answering  key questions such as:

- Analysing relation between online order and rating.
- Analysing customer reviews using bi-gram anf tri-gram analysis.
- To understand where restaurants are concentrated and identify areas with high or low restaurant density.

### Results

The analysis result are summarized as follows:

- Highly rated resturants take more online orders as compared to low rated resturants.
- Positive reviews often featured tri-grams such as "must visit place", "The food good", and "best restaurant ever."


### Limitations

Found many missing data , had to delete those rows.

### Tools and Libraries

- Python: The main programming language used for the project.
- pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- TextBlob: For sentiment analysis.
- Matplotlib and Seaborn: For data visualization.
- WordCloud: For creating word clouds.
- emoji: For emoji analysis
- string: for analysis the effect the use punctuation in title on likes and views
