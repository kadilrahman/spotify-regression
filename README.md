# spotify-regression
 Objective  The objective of the challenge is to build a **machine learning model** that is able to predict the **popularity score** of a song. Popularity of a song is a continuous numerical value and this problem statement is a **regression problem**.
## Dataset

There are two files `CS98XRegressionTrain.csv` that contains the training dataset and `CS98XRegressionTest.csv` that contains the dataset for final testing. The dataset is a collection of spotify songs with their **audio features** (tempo, energy, danceability etc.) The training dataset contains 15 columns that are described below:

- `Id` - an arbitrary unique track identifier
- `title` - track title
- `artist` - singer or band
- `top genre` - genre of the track
- `year` - year of release (or re-release)
- `bpm` - beats per minute (tempo)
- `nrgy` - energy: the higher the value the more energetic
- `dnce` - danceability: the higher the value, the easier it is to dance to this song
- `dB` - loudness (dB): the higher the value, the louder the song
- `live` - liveness: the higher the value, the more likely the song is a live recording
- `val` - valence: the higher the value, the more positive mood for the song
- `dur` - duration: the length of the song
- `acous` - acousticness: the higher the value the more acoustic the song is
- `spch` - speechiness: the higher the value the more spoken word the song contains
- `pop` - popularity: the higher the value the more popular the song is (and the target variable for this problem)

## Approach

The approach of our group towards solving this problem is by using various regression models like Catboost Regressor, Stochastic Gradient descent Regressor, Support Vector Regression, Decision Tree, Random Forest Regressor and Gradientboost Regressor so as to choose the regression model showcasing optimum efficiency. In order to progress towrads this ultimate output, we have performed various preliminary operations on the datasets which include cleaning the datasets and visualizing relationships between various features and target variable (i.e Popularity) using Exploratory Data Analysis. 

## Required python libraries

- [Numpy](https://numpy.org/) - for numerical operations
- [Pandas](https://pandas.pydata.org/) - for loading, querying and manipulating datasets
- [Matplotlib (pyplot)](https://matplotlib.org/3.5.3/api/_as_gen/matplotlib.pyplot.html) - for visual analysis
- [Seaborn](https://seaborn.pydata.org/) - for visual analysis
- [Scikit-Learn](https://scikit-learn.org/stable/) - for machine learning
- [Catboost](https://catboost.ai/en/docs/concepts/python-reference_catboostregressor) - for CatBoost Regressor Model
