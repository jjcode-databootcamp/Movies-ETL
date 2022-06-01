# Movies-ETL

## Overview 
The goal of this project is to automate the data pipeline using "Extract -> Transform -> Load" method on different sources of movie data into an PostgreSQL table.

Source and type of data:
- Wikipedia (JSON)
- Kaggle Metadata (CSV)  
- Rating (CSV)

## Process 

1. Load All Data Files Into Dataframes- Create a new jupyter notebook to write a function to read the three data files into different dataframes 
  - [ETL_function_test](ETL_function_test.ipynb)
2. Extract and Transform - Filter out TV shows, removed duplicate records, consolidated the redundant records and format the data sets.
  - [Clean Wikipedia Data](ETL_clean_wiki_movies.ipynb)
  - [Clean Kaggle Metadata and Ratings Data](ETL_clean_kaggle_data.ipynb)
    
3. Load the clean data to a PostgreSQL Movie Database and tables
  - [Create and Load PostgreSQL Movie Table](ETL_create_database.ipynb)


![Movies Query](https://github.com/jjcode-databootcamp/Movies-ETL/blob/main/Resources/movies_query.png)


![Ratings Query](https://github.com/jjcode-databootcamp/Movies-ETL/blob/main/Resources/ratings_query.png)
