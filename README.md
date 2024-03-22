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
[text](blob:vscode-webview%3A//091mek6iqrvu0ifqovokkigj5mhgm1ds2m3g6mk3g1n175hu5tks/bcddb1f9-c47b-4f68-8ab4-d40fbc982249)

Results on the most profitable genre
There is a positive correlation between production budget and worldwide grss.I would recommend Microsft to budget for genres that require high budget

[text](blob:vscode-webview%3A//091mek6iqrvu0ifqovokkigj5mhgm1ds2m3g6mk3g1n175hu5tks/20ee06bd-4eb3-4388-8790-05f9dbaf1177)

Results on the most rated movie genres[text](blob:vscode-webview%3A//091mek6iqrvu0ifqovokkigj5mhgm1ds2m3g6mk3g1n175hu5tks/00aad64c-c117-4f59-b322-d8061b5e879c)



### Recommendations
- I will recommend Microsoft to focus on Drama, Then Documentary followed closely by Comedy Genres. The movie genres are likely to do well
- I would recommend Microsft to budget for genres that require high budget

- Microsoft should focus short type of movie genre because it highly rated


### Conclusion

Since these are just basic visualizations it is hard to fully evaluate the effectiveness of the recommendations
These recommendations also don't guarantee that a successful movie will be made. Just knowing what genres perform the best and that more should be spent on budget will only get you so far. Removing the outliers would have provided a more accurate Pearson's correlation coefficient for production budget vs worldwide gross. 