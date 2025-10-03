# Spotify-Regression
A regression study to predict the danceability of songs for a hypothetical audience of sound engineers and music producers at a major Australian record label.

![genre_plots](https://github.com/user-attachments/assets/7aca55bc-2e63-4cd5-807f-0cded231229f)

![tie_plots](https://github.com/user-attachments/assets/7bb47945-665a-441c-b71b-084a9b6d4fd4)
The above OLS coefficient estimates and their 95% confidence intervals present some interesting findings. The following terms have significant relationships with danceability:
- **genre_rap_hiphop** has a highly significant positive effect, strongly associated with a higher danceability score
- **genre_edm** has a significantly positive effect, associated with a higher danceability score
- **valence** has the strongest positive effect. Tracks with higher valence (i.e. they sound more positive, happy, or cheerful) are associated with a higher value of the dependent variable
- genres for **metal**, **punk**, **country**, **jazz**, and **rock** are associated with a lower danceability score
- **acousticness_log** has a significant negative effect on danceability
- **energy** has the largest magnitude negative effect. Tracks with higher energy are strongly associated with lower danceability.
