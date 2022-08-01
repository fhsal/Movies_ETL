# Movies_ETL

CWRU Data Analytics Module Eight Challenge


## Overview of Project

The project involved loading movie data regarding wide-ranging information (~190+ attributes) such as movie title,  director, box office revenue, producers, screenplay, ratings, etc. from different sources (Wikipedia, Kaggle, MovieLens) into pandas dataframes, consolidating and merging that data and storing the results into a Postgress database.  

### Summary

The effort involved extracting the data from csv and json files, transforming the data by cleaning and normalizing it so that information from the three sources could be merged and then loading the results into SQL tables in a 'movie_data' database. 

## Major components of the analysis:


* Deliverable 1: creating an ETL function load the wikipedia, kaggle and ratings data (using regex) 

* Deliverable 2: creating a function to load and clean the wikipedia data

* Deliverable 3: creating a function to load and clean the kaggle data

* Deliverable 4: creating a function to load, clean and merge the kaggle, wikipedia and ratings data - and then write the results to an SQL database 