# Film Analysis

## Project Overview

For this project, you will use exploratory data analysis to generate insights for a business stakeholder.
Descriptive analysis of some movies had achieved high Box office earnings. The outcome data shows three recommandations,Microsoft Company can use this analysis to decide how to produce a successful movie.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

### Results
Results on the most popular type of genre
![alt text](f9070e59-47c2-4e2d-84b1-104a91b1c1bb.png)

Results on the most profitable genre
There is a positive correlation between production budget and worldwide grss.I would recommend Microsft to budget for genres that require high budget

![alt text](5b942e9f-bfb9-4368-861f-4f2c084415d2.png)

Results on the most rated movie genres
![alt text](6b09c980-09ad-4338-a368-16a841ced51b.png)


### Recommendations
- I will recommend Microsoft to focus on Drama, Then Documentary followed closely by Comedy Genres. The movie genres are likely to do well
- I would recommend Microsft to budget for genres that require high budget

- Microsoft should focus short type of movie genre because it highly rated


### Conclusion

Since these are just basic visualizations it is hard to fully evaluate the effectiveness of the recommendations
These recommendations also don't guarantee that a successful movie will be made. Just knowing what genres perform the best and that more should be spent on budget will only get you so far. Removing the outliers would have provided a more accurate Pearson's correlation coefficient for production budget vs worldwide gross. 