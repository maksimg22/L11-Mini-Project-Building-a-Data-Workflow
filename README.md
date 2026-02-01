# Open Data ETL Mini-Project

## Project Overview

This project demonstrates a simple data workflow built using Python and pandas.  
An open dataset is extracted, transformed with multiple data-cleaning steps, and saved as a clean CSV file for future analysis or dashboard use.

The goal of this project is to practice building a small but complete data pipeline and publishing it to GitHub.

## Data Source

Data set used in this project was taken from https://www.kaggle.com/datasets/wardabilal/spotify-global-music-dataset-20092025?resource=download

## Workflow Type

ETL: Extract → Transform → Load

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

## Transformations 

- The initial data set was cleaned. 
- Basic information about the data set such as data types, shape, descriptive statistics was found.
- New column release_day_of_week was added.
- Processed data was saved as spotify_data_processed.csv

## How to run

Use the script from crs/main.py

## Output

The code creates processed data file spotify_data_processed.csv which contains:
- clean data
- new column release_day_of_week

Also, script shows: first 5 rows, shape, data types, descriptive statistics.

## Example output

```output
track_id	track_name	track_number	track_popularity	explicit	artist_name	artist_popularity	artist_followers	artist_genres	album_id	album_name	album_release_date	album_total_tracks	album_type	track_duration_min
0	3EJS5LyekDim1Tf5rBFmZl	Trippy Mane (ft. Project Pat)	4	0	True	Diplo	77	2812821	moombahton	5QRFnGnBeMGePBKF2xTz5z	d00mscrvll, Vol. 1	2025-10-31	9	album	1.55
1	1oQW6G2ZiwMuHqlPpP27DB	OMG!	1	0	True	Yelawolf	64	2363438	country hip hop, southern hip hop	4SUmmwnv0xTjRcLdjczGg2	OMG!	2025-10-31	1	single	3.07
2	7mdkjzoIYlf1rx9EtBpGmU	Hard 2 Find	1	4	True	Riff Raff	48	193302	NaN	3E3zEAL8gUYWaLYB9L7gbp	Hard 2 Find	2025-10-31	1	single	2.55
3	67rW0Zl7oB3qEpD5YWWE5w	Still Get Like That (ft. Project Pat & Starrah)	8	30	True	Diplo	77	2813710	moombahton	5QRFnGnBeMGePBKF2xTz5z	d00mscrvll, Vol. 1	2025-10-31	9	album	1.69
4	15xptTfRBrjsppW0INUZjf	ride me like a harley	2	0	True	Rumelis	48	8682	dark r&b	06FDIpSHYmZAZoyuYtc7kd	come closer / ride me like a harley	2025-10-30	2	single	2.39
```





