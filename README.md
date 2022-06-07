# AnimeRegressionScoring
Trying to predict an Anime's MyAnimeList score (rating) via regression models. Score being a primary way of interpretting popularity/success for an anime in any given season.

<sub>Final group project for Intro to Data Mining</sub>

## Deployment
Run it on [Colab](https://colab.research.google.com/github/Cristian-Solis/AnimeRegressionScoring/blob/main/AnimeRegressionScoring.ipynb)!

## Data Sources
1. [Kaggle](https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020)
2. [MyAnimeList Spring 2022 Seasonal Anime](https://myanimelist.net/anime/season)
## My Contribution
  1. Cleaned [`anime_2022_2.csv`](https://github.com/Cristian-Solis/AnimeRegressionScoring/blob/main/anime_2022_2.csv) `Genre` and `Studio` features to match [`anime.csv`'s](https://github.com/Cristian-Solis/AnimeRegressionScoring/blob/main/anime.csv) formatting.
  2. Binarized `Genre`
  3. Combined [`anime_2022_2.csv`](https://github.com/Cristian-Solis/AnimeRegressionScoring/blob/main/anime_2022_2.csv) and [`anime.csv`](https://github.com/Cristian-Solis/AnimeRegressionScoring/blob/main/anime.csv) to combine older and newer anime. 
  4. Created `Genre` and `Type Of Media` visualizations to showcase each feature's unique values.
  5. Worked on Random Forest Regression Model
      - Tried singular features to see how they would fare in predicting score (ratings)
      - Tried combination of features to see how they would stack up against singular features in terms of score
      - Optimized the best model by dropping zeros to get better MSE and score ($R^2$) values when predicting score
  6. Predicted Dragon Ball's score using Random Forest Model
