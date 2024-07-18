## Group 1 Project 1 - Mo Money$ Movie$

### How to Make The Most Money$ with One Movie

### Introduction

We are representatives of a small indie film company, Mo Money$ Movie$. Our shared love for movies and making money has brought us together. Our focus is to determine how to maximize profits from a single movie to grow our company and continue our filming journey. In order to do this, we are using OMDb and IMDb API and databases to analyze movie budgets, profits, and ratings.

### Project Scope  
We will be analyzing movies between the years of 2005-2015. This decade was chosen to take into consideration the rise of streaming platforms and avoid COVID-related data. We do not discriminate against any production company that will give us money!

### Key Metrics
We will analyze:
- Total movie budget
- Total movie profit
- Movie genre
- Total ratings
- Critic vs general audience ratings

### Movie Selection Criteria
In addition to years, our movies will also be limited to the top 50 movies of each year. The “top” movies will be determined using number of ratings in order to avoid including movies which have only two 100% votes. By utilizing this method of number of votes, we believe we will be pulling the most watched and therefore most paid-for movies. 

### Potential Questions
- What is the correlation between the movie budget and its profit?
- Is there an optimal budget range that maximizes profits?
- Are there any observable trends that correlate with the rise of streaming platforms?
  
- Which genres are most profitable?
- Do certain genres perform better with lower budgets?
- What are the average budget and profit for top genres.
  
- How do critic ratings compare to general audience ratings in terms of impact on profits?
- Is there a significant difference in profitability between highly-rated movies and poorly-rated movies?
- Does the number of ratings correlate with profitability?

### API's
- *OMDB* - basic info - ratings, title, boxoffice
- *TMDB* - more extensive data and financials
- POSSIBLE - Box Office Mojo - (Need imdbpro??) detailed revenue data

#### Major Roles:
- *Chris: Proj prep and API* - Project and repo init. Choose and ensure proper API keys configuration and data fetching.
  
- *Jack: Budget/Profititability* - Explore and answer financial related questions with the use of exploration and charts. (Account for inflation per year? Too annoying?)
  
- *Sarah: Ratings* - Aggregate (and standardize?) ratings from decided sources. Explore and answer questions related to ratings and profitability. Options from OMDB are: IMDB Value, IMDB Rating, Metacritic, Rotten Tomatoes. Maybe use only the source with highest number of ratings?
  
- *Chuck: Genre* - Use consistent genre categories to ensure comparability across different data. Explore genre data and compare to ratings and profitablity to answer questions.
