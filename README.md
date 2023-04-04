# Mutual-Fund-Analysis

Mutual Fund Analysis

This project aims to analyze the performance and risk of three hypothetical mutual funds using the R programming language in a Jupyter notebook (with R kernel).

Data

The analysis will be conducted using three data sources:

Fund Data - Monthly return data for three hypothetical mutual funds. (https://www.dropbox.com/scl/fi/i84z3g58ccgf1dg9cmd0m/Funds.xlsx?dl=0&rlkey=yzgks0t96n6cnxu6amau6p1qo)
Benchmark Data - Monthly return data for a benchmark that we will assume is the benchmark for the three mutual funds. (https://www.dropbox.com/scl/fi/9i1vutbd5908vw1g8qfjm/Bmark.xlsx?dl=0&rlkey=mcj64ud1cak14rbkjdwtc8fiv)
Factor Data - The Fama/French Developed 3 Factors dataset, which will be sourced from the Ken French data library at the following address: http://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html
Analysis

The analysis consists of two parts:

1. Vs. Benchmark Analysis - We will look at three metrics of relative performance and risk versus the given benchmark for the three funds:
- Annualized ex-post tracking error
- Annualized information ratio
- Beta relative to the benchmark
2. Vs. Factor Model - We will use the Fama-French Developed 3-Factor model to compare each of these returns against. A basic linear regression will be run for each fund versus this 3-factor model.
Results

The output will be a set of results providing insights into the performance and risk of the three hypothetical mutual funds. The results will be presented in data frames and visualizations generated by the R script.

To run the analysis, make sure to place the Fund Data and Benchmark Data files in the working directory, and run the R script provided in the Jupyter notebook. The results will be displayed within the notebook.

Required Libraries

The following libraries are required for this analysis:

- readxl
- tidyverse
- httr
- readr
- lmtest


