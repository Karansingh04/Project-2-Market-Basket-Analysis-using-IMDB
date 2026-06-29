# IMDB Market-Basket Analysis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Karansingh04/IMDB-Market-Basket-Analysis/blob/main/Project2_IMDB_Market_Basket_Analysis.ipynb)

Implementation of market-basket analysis on the IMDB Movies Dataset for Project 2 of Algorithms for Massive Data.

## Project Overview

This project treats each movie as a basket and the actors listed in `Star1`, `Star2`, `Star3`, and `Star4` as items. A custom Apriori implementation is used to identify frequent actor collaborations. The algorithm is from the course syllabus section on frequent itemsets and market-basket analysis.

The project includes:
- IMDB dataset loading through Kaggle or local CSV fallback
- Movie-to-basket data organisation
- Actor-name cleaning and deduplication within movies
- Custom Apriori frequent itemset mining
- Support-threshold experiments
- Scalability analysis

## Dataset

Source: IMDB Dataset of Top 1000 Movies and TV Shows on Kaggle  
Kaggle identifier: `harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows`

Fields used:
- `Series_Title`
- `Star1`
- `Star2`
- `Star3`
- `Star4`

## Repository Structure

- `Project2_IMDB_Market_Basket_Analysis.ipynb` : Main notebook
- `Project2_Report.pdf` : Project report
- `Project2_Report.tex` : LaTeX source file
- `README.md` : Repository description

## Main Results

Using minimum support 3:
- 271 frequent actors
- 25 frequent actor pairs
- 3 frequent actor triples
- 0 frequent actor quadruples

The strongest recurring actor triple is Daniel Radcliffe, Emma Watson and Rupert Grint, reflecting the repeated cast structure of the Harry Potter films.

## Author

Karan Singh  
MSc Data Science for Economics  
Universita degli Studi di Milano
