# Spotify Top 50 Tracks of 2020

Exploratory analysis of Spotify's 50 most streamed tracks of 2020 with pandas: artists, albums, genres, track
length and audio features such as danceability, loudness and acousticness.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pboric/spotify-top-tracks-analysis/blob/main/Top_50_Spotify_Tracks_of_2020.ipynb)

## Key findings

- **Billie Eilish, Dua Lipa and Travis Scott** have three tracks each in the top 50; in total 40 artists and 45
  albums appear. Dua Lipa's *Future Nostalgia* is the only album with three tracks.
- **Pop** is the most common of 16 genres.
- *SICKO MODE* is the longest track and *Mood (feat. iann dior)* the shortest.
- **Energy and loudness** are the only strongly correlated audio features (r = 0.79); no pair is strongly negatively
  correlated.
- Hip-Hop/Rap (0.77) and Dance/Electronic (0.76) are the most danceable genres; Alternative/Indie is by far the most
  acoustic (0.58, against 0.10 for Dance/Electronic).

## What the notebook covers

Each section answers one question: the size of the dataset, artists and albums with several hits, the most popular
artist and genre, tracks above or below danceability and loudness thresholds, the longest and shortest tracks,
correlations between audio features, and genre comparisons.

## Run it

```bash
pip install -r requirements.txt
jupyter notebook Top_50_Spotify_Tracks_of_2020.ipynb
```

The notebook downloads the data from Kaggle with `opendatasets`, which asks for your Kaggle username and API key.

## Data

[Top 50 Spotify Tracks 2020](https://www.kaggle.com/datasets/atillacolak/top-50-spotify-tracks-2020) on Kaggle.

## License

MIT
