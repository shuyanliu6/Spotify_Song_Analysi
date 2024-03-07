# spotify-songs-analysis
Using a dataset of 52k songs, better understand what makes music popular as well as the audio features that make up specific genres. Our final report (found under `final_report.pdf`) answers the following questions:
1) Is there a relationship between song length and popularity of a song? If so, is it positive or negative?
2) Are explicitly rated songs more popular than songs that are not explicit?
3) Are songs in major key more popular than songs in minor key?
4) Which of the following 10 song features: duration, danceability, energy, loudness, speechiness,
acousticness, instrumentalness, liveness, valence and tempo predicts popularity best?
How good is this model?
5) Building a model that uses *all* of the song features mentioned in question 1, how well can you
predict popularity? How much (if at all) is this model improved compared to the model in question
4). How do you account for this? What happens if you regularize your model?
6) When considering the 10 song features in the previous question, how many meaningful principal
components can you extract? What proportion of the variance do these principal components
account for? Using these principal components, how many clusters can you identify? Do these
clusters reasonably correspond to the genre labels in column 20 of the data?
7) Can you predict whether a song is in major or minor key from valence using logistic regression or a
support vector machine? If so, how good is this prediction? If not, is there a better one?
8) Can you predict genre by using the 10 song features from question 4 directly or the principal
components you extracted in question 6 with a neural network? How well does this work?
9) In recommender systems, the popularity based model is an important baseline. We have a two part
question in this regard: a) Is there a relationship between popularity and average star rating for the
5k songs we have explicit feedback for? b) Which 10 songs are in the “greatest hits” (out of the 5k
songs), on the basis of the popularity based model?
10) You want to create a “personal mixtape” for all 10k users we have explicit feedback for. This
mixtape contains individualized recommendations as to which 10 songs (out of the 5k) a given user
will enjoy most. How do these recommendations compare to the “greatest hits” from the previous
question and how good is your recommender system in making recommendations?

The code used for analysis is under `code.ipynb`.

