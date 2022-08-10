# Movies-ETL

### Overview.

I have been assign a project for Movie-ETL for extract, transform , clean the data and load the new clean data. Code is extracted from Wikipedia.JSOn, movies-metadata.csv and MovieLens rating csv, transform the data with regex and loads the data into PostgreSQL database.

### Resources


Extract - ETL_function_test.ipynb

Transform - ETL_clean_wiki_movies.ipynb & ETL_clean_kaggle_data.ipynb

Load - ETL_create_database.ipynb

Languages: Python, SQL

Tools: Jupyter Notebook, JSON, Pandas, NumPy, sqlalchemy, psycopg2

Data Source(s): wikipedia.movies.json, movies_metadata.csv, ratings.csv (note: due to large file size, I am unable to push ratings.csv to repo)


### Result


The resulting database consists of two tables that are highlighted below.

A movies table with 6,051 rows of data, each representing a unique movie title. The table also includes 31 columns of data with production related information, such as, movie budget, producers, actors and release data.

<img width="335" alt="movies_query" src="https://user-images.githubusercontent.com/107137215/183973221-83f866e5-414e-489b-b373-8eb9cf46ba2e.png">

A ratings table a table with 26,024,289 rows of data, each representing a viewer rating of 1-5. The table also includes 5 columns of data such as movie title, rating and date. 


<img width="313" alt="ratings_query" src="https://user-images.githubusercontent.com/107137215/183973316-2dfc59b4-7611-4b2c-832f-0448cc00dec9.png">
