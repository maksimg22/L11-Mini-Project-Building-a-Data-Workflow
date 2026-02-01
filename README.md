# Open Data ETL Mini-Project

## Project Overview

This project demonstrates a simple data workflow built using Python and pandas.  
An open dataset is extracted, transformed with multiple data-cleaning steps, and saved as a clean CSV file for future analysis or dashboard use.

The goal of this project is to practice building a small but complete data pipeline and publishing it to GitHub.

## Data Source

Data set used in this project was taken from https://www.kaggle.com/datasets/wardabilal/spotify-global-music-dataset-20092025?resource=download

## Workflow Type

ETL: Extract → Transform → Load

## Transformations 

- The initial data set was cleaned. 
- Basic information about the data set such as data types, shape, descriptive statistics was found.
- New column release_day_of_week was added.
- Processed data was saved as spotify_data_processed.csv

## Project Structure

```text
L11-Mini-Project-Building-a-Data-Workflow/
├── data/
│ ├── raw/ # Raw dataset (optional)
│ └── processed/
│ └── output.csv # Final cleaned dataset
├── src/
│ └── main.py # ETL script
├── README.md # Project documentation
├── requirements.txt # Python dependencies
└── .gitignore
```



