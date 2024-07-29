## Group 1 Project 1 - Mo Money$ Movie$

### How to Make The Most Money$ with One Movie

### Introduction

We are representatives of a small indie film company, Mo Money$ Movie$. Our shared love for movies and making money has brought us together. Our focus is to determine how to maximize profits from a single movie to grow our company and continue our filming journey. In order to do this, we are using OMDb and IMDb API and databases to analyze movie budgets, profits, and ratings.

### Project Scope and Criteria Selection
We will be analyzing movies between the years of 2005-2015. This decade was chosen to take into consideration the rise of streaming platforms and avoid COVID-related data. We do not discriminate against any production company that will give us funding money! Movies below a Budget or Revenue below $5000 will be removed from analysis. A Kaggle database of over 45,000 movies was used as our initial data set to retrieve movie titles, years and financial information. This was then cross referenced with OMDB API by IMDB ID to collect all of our Ratings information.

### Key Metrics
    - Total movie budget
    - Total movie revenue
    - Return on investments
    - Movie genre
    - Rating value
    - Total ratings

### Questions:
    - Does budget affect overall profit?
  
    - Do ratings need to be high to be profitable?
      
    - Do any genres stand out as big money makers?


### Resources, Cites and API
- *OMDB* - ratings, titles etc- https://www.omdbapi.com/
- *Kaggle* - The Movies Dataset - contains financial info not present on OMDB - [https://www.kaggle.com/code/danofer/movies-data-clean/input?select=movies_metadata.csv](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv)
- str.contains - found on StackOverflow - https://stackoverflow.com/questions/37011734/pandas-dataframe-str-contains-and-operation
- Set code for genres data shared by Othmane (Thank you!)

#### Major Roles:
- *Chris: Proj prep and API* - Project and repo init. Choose datasets and ensure proper API keys configuration and data fetching. Data cleaning and prepping. PPT slideshow
  
- *Jack: Budget/Profititability* - Explore and answer financial related questions with the use of exploration and charts, then compare by genres. 
  
- *Sarah: Ratings* - Aggregate ratings from sources. Explore and answer questions related to ratings, profitability and genre. Presentation Doc creation.
  
- *Chuck: Genre* - Use consistent genre categories to ensure comparability across different data. Explore genre data and compare to ratings and profitablity to answer questions.



### This repo contains the following files:
    Root\
    - clean_dataset.ipynb - The Jupyter Notebook containing code for dealing with the kaggle dataset: cleaning, filtering and file export
    - mo_movies.ipynb - The Jupyter Notebook containing code for api, data parsing and merging, filtering and file exports
    - mo_genres - The Jupyter Notebook containing code and analysis for exploration by genre
    - movies_ratings.ipynb - The Jupyter Notebook containing code and analysis for exploration by ratings
    - jack_budgets.ipynb - The Jupyter Notebook containing code and analysis for exploration by finances
    - MoMoviesClassPresentation.pptx - Powerpoint presentation of EDA
    - How to earn the highest profit from a single movie.docx - Word doc with presentation overview and explanation
    
    Resources\
    - movies_metadata.csv - financial dataset from Kaggle
    - filtered_movies_data.csv - prep file. created from cleaning and filtering the kaggle dataset
    - mo_movies_data.parquet - file export that contains the data frame for the EDA work
    - mo_movies_data.csv - alternate file export that contains the data frame for the EDA work in CSV format

