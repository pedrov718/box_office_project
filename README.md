# box_office_project
## An anlysis on box office data.

## Overview

This is project with Exploratory Data Analysis of what Microsoft, if it theoretically created a film studio, should do to become a successful movie studio. Ater collecting data, we decided the best way to do this was divide the movies in our dataset into 3 tiers based on budget, and do anlayses on the subsets based on other variables. After doing this and visualizing our results, we came to the conlusion that the best way for Microsoft to maximize profits for its new movie studio was based on 3 criteria: genre, directors, and release month, for each budget tier. 

## Business Understanding

We are working for Microsoft Studios, and have to present to our head company, Microsoft, 3 concrete business suggestions they can use to success as a film studio.

## Data Understanding and Analysis

Our data came from the budget dataframe provided by Flatiron, the director information in the SQL relational database, and data webscraped from IMDB’s list of top 200 grossing movies for each year between 2012 and 2022. After cleaning the data we had information from roughly 1500-1600 movies to work with. Our plan was to find the most profitable movies, after the data was divided into 3 subsets based on budget tier, low budget movies costing less than $5 million, mid budget movies costing between $5 and $50 million, and high budget movies costing over $50 million. After this, we analzyed the subsets on the criteria of genre, director, and release month, to see which values in these 3 categories were the most profitable for each budget tier.  For blockbusters, we also included runtime.

## Description of data

![alt text](https://i.postimg.cc/Prsz8pvT/avg-boxoffice-permonth-bar.png)
![alt text](https://i.postimg.cc/Yq6NNrQg/avg-domestic-gross-by-dist.png)
![alt text](https://i.postimg.cc/QtK1FhXF/avg-profit-per-genre-all-years.png)
![alt text](https://i.postimg.cc/FKRjQ08g/avg-rating-vs-profit.png)
![alt text](https://i.postimg.cc/K8QnV0q8/avg-runtime-per-genre.png)
![alt text](https://i.postimg.cc/prN884Tq/avg-runtime-vs-profit.png)
![alt text](https://i.postimg.cc/ZKSp5GXq/boxoffice-per-month-2012-2022.png)
![alt text](https://i.postimg.cc/YCt6b5xP/boxoffice-per-year-line.png)
![alt text](https://i.postimg.cc/1zjDRfZx/movie-data-erd.jpg)
![alt text](https://i.postimg.cc/HkWMQQYD/profitable-directors.png)
![alt text](https://i.postimg.cc/4NQt78TQ/profit-margin-vs-num-opening-theaters.png)
![alt text](https://i.postimg.cc/SxZMVJRX/total-opening-theaters-vs-profit.png)


## Conclusion

For a low budget movie, the best movie to make was in the horror genre, have the director be Jordan Peele or Christopher Landon, and have the movie be released in January or October. 

For mid budget movies, the best way to make the most money is to make a horror movie directed by Andy Mushcietti, or make a action movie released by Olivier Megaton. Either movie should be released in July, November, or December. 

For high budget movies, or blockbusters, the best way to maximize profit is to make a movie that is in the genres of Animation, Action, or Adventure, have the director be Anthony Russo, Colin Trevorrow, or James Wan, and to release the movie in May, June, or July, Also, we found the most ideal runtime for a blockbuster is between 125 and 150 minutes. 







