# Microsoft Movie Studios Recommendations

## Project Overview

This project analyzes movie data from movie aggregation websites to create proposals for a hypothetical new Microsoft Movie Studios. The analysis shows that movies which met a budget threshold or released during peak months typically yielded greater profits. Additionally, documentaries were the top-rated genre. Microsoft can leverage these three business insights for producing successful movies.

## Business Understanding

Our client is a hypothetical new Microsoft Movie Studios. The goal of our analysis is to provide suggestions to help Microsoft decide what kind of movies to produce. We conducted an analysis on movie data to construct three actionable insights that Microsoft can utilize to find success in their movie-making venture.

## Data Understanding and Analysis

Our data is stored in a folder named zippedData. The data is sourced from a variety of movie aggregation sites: IMDB, Box Office Mojo, Rotten Tomatoes, TheMovieDB, and The Numbers. 

Data gathered from IMDB included movie genres, average ratings, and the number of votes received. The data was joined to view all relevant data on one table. 

The data we analyzed from the other sources includes budgets, domestic/worldwide gross, and release date.

## Results
![Correlation between runtime and rating](/correlation_between_runtime_and_average_rating.png)

It is evident that there is positive correlation between the length of the movie with the chances of getting a high rating.

![Return on investment vs genres](/return_on_investment_vs_genres.png.png)

The graph of return on investment vs which genres suggests that the top 5 genres that have the highest return on investment are:
1. Mystery
2. Horror
3. Thriller
4. Music
5. Animation

This can be a valid inference as the making of such movies would require a higher budget to go into costumes, CGI/ graphics etc. 
Each of the top 5 probably had a high budget as all these come into play in their making


![Average rating vs genres](/rating_vs_genres.png.png)
This graph of genres to avg_rating shows that the top 5 more highly rated genres are:
1. Biography
2. Animation
3. Drama
4. Sci-fi
5. Romance
The validity of this inference cannot be determined.

