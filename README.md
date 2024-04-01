# audio-rec-algo

A comprehensive machine learning pipeline that satisfies the patterned steps of a classic machine learning project on a rendition of "Music Dataset: Lyrics and Metadata from 1950 to 2019".

<div style="text-align:center">
  <img src="images/Cover.jpg">
</div>

## Data Overview

The columns of the dataset were as follows:

- artist_name: The name of the artist
- track_name: The name of the song
- release_date: When this song was released
- genre: The categorical genre of this song
- lyrics: The pre-tokenized lyrics of this song. Disclaimer: note that as this is real-world
  data, lyrical content is often obscene.
- len: The number of words in the lyrics of this song
- dating: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with dating.
- violence: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with violence.
- world/life: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with the world or life in general terms.
- night/time: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do night-life or time.
- shake the audience: A score from 0 to 1 expressing how likely it is that this song’s lyrics
  have something to do with provocative feeling.
- family/gospel: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with family-oriented content or the gospel.
- romantic: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with romantic feeling.
- communication: A score from 0 to 1 expressing how likely it is that this song’s lyrics
  have something to do with communication (either in romantic terms or otherwise).
- obscene: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with obscene content (money, rockstar-lifestyle, etc).
- music: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with music (music about music, basically).
- movement/places: A score from 0 to 1 expressing how likely it is that this song’s lyrics
  have something to do with movement or various locations.
- light/visual perceptions: A score from 0 to 1 expressing how likely it is that this song’s
  lyrics have something to do with the sun or other physical weather-related patterns.
- family/spiritual: A score from 0 to 1 expressing how likely it is that this song’s lyrics
  have something to do with the importance of family or spirituality.
- sadness: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with the importance of family or spirituality.
- feelings: A score from 0 to 1 expressing how likely it is that this song’s lyrics have
  something to do with emotions, either positive or negative.
- topic: The categorical label of lyrical content
- age: A score from 0 to 1 expressing how “old” a song is from our perspective. 1 being
  the oldest, and 0 being the newest.

## EDA

[Exploratory Data Analysis](https://github.com/nasehacho/audio-rec-algo/blob/main/notebooks/01-Audio-Data-Initial-EDA.ipynb)

## Pre-Processing

[Data Pre-Processing](https://github.com/nasehacho/audio-rec-algo/blob/main/notebooks/02-Audio-Data-Pre-Processing.ipynb)

## Data Modeling

[Data Modeling](https://github.com/nasehacho/audio-rec-algo/blob/main/notebooks/03-Audio-Data-Modeling.ipynb)

## New Predictions

[New Sample Prediction](https://github.com/nasehacho/audio-rec-algo/blob/main/notebooks/04-Audio-Data-New-Sample-Prediction.ipynb)

## Audio Report

[Data Report](https://github.com/nasehacho/audio-rec-algo/blob/main/notebooks/05-Audio-Data-Report.ipynb)
