# Modeling monthly business formations and applications in the USA - by Felix Reichel

This repository provides data and a jupyter notebook to analyse the business formation statistics from the [United States Census Bureau](https://www.census.gov/econ/bfs/current/index.html).
The dataset contains the number of business applications (adjusted for seasonal variation) in the United States and geographical subregions, sorted by sectors and types of applications. 
The dataset contains numbers from mid-2004 until February 2025.


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You need to install the following Python libraries to run the code in the analysis notebook: 
- `numpy` 
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`


## Project Motivation<a name="motivation"></a>

For this project, I was interested in using the USCB Business Formation Statistics to address the following questions:

1. How can we best model the number of business applications per month over time? Is it feasible to predict future application numbers from previous data?
2. How did the trend in applications change after the COVID-19 pandemic compared to data before 2020?
3. Can the data from the pre-Covid times be used to predict trends after 2020?


## File Descriptions <a name="files"></a>

The repository contains two files for analysis:
- `bfs_monthly.csv`: Monthly business formation data downloaded from the USCB webpage
- `analysis.ipynb`: Notebook for data analysis
- 

## Results<a name="results"></a>

The main findings of the code can be found in [this post](https://felix-r.github.io/).


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The data is provided by the United States Census Bureau. 

