# Assignment 01 – Netflix Titles Analysis  
Jamie Jones  
CS4347G: Data Analysis & Visualization  

## Overview

This repository contains my submission for Assignment 01.  
The project analyzes the Netflix Titles dataset using Python (pandas, matplotlib, seaborn) in a Jupyter Notebook.

The main research question investigated is:

**Which countries contribute the most Netflix titles, and how has the number of titles added from those countries changed over time?**

---

## Dataset

The dataset used is the Netflix Titles dataset provided in Lecture 3.  
It includes information such as:
- Title type (Movie or TV Show)
- Country
- Release year
- Date added to Netflix
- Rating
- Duration
- Genre categories

---

## Methods

The notebook includes:
- Data cleaning (handling missing values, parsing dates, removing duplicates)
- Creation of a cleaned `primary_country` column
- Grouped summaries to identify top contributing countries
- Trend analysis of titles added over time
- Visualizations (bar chart and line chart)

---

## Key Findings

- The United States contributes the largest number of titles by a significant margin.
- Several other countries such as India and the United Kingdom also contribute substantially.
- The number of titles added increased sharply after 2015, reflecting Netflix’s rapid global expansion.
- Growth appears to level off in recent years.

---

## How to Run

1. Clone this repository: git clone https://github.com/jamiejones8/cs4347assignment01
2. Open the `analysis.ipynb` file in Jupyter Notebook or JupyterLab.
3. Run all cells from top to bottom.

Required libraries:
- pandas
- numpy
- matplotlib
- seaborn

