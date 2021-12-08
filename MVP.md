# Prediction of top IMDB rating movies

The goal of this project is to understand which factors are most important in effect the rating of the imdb movies.

To reach the expected goal we used regression model by looking to the features of each movie ('IMDB_RATE','years','metascore','timeMin','votes','US_grossM') and find the correlation between them to extract the most factors that affect the rating of any movie.

<img width="426" alt="Screen Shot 2021-12-08 at 1 52 28 PM" src="https://user-images.githubusercontent.com/93079431/145196075-addd56ad-dcf3-4d3f-9650-eebdef79c318.png">

The result of the figure suggest that the IMDB rating got high correlation with US_grossM 0.56 but got a higher correlation with votes with a value of 0.6
Therefore, We can build a model that will estimate the rating based on the most effective factors.
