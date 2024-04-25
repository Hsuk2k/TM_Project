# Music Recommender System
### Bas Goossens, Fatemah Iqbal and Kushagra

## Abstract
This project seeks to create a music recommendation system utilizing collaborative filtering techniques. Our system will integrate conventional filtering factors such as similar artists, lyrics, and BPM. However, our primary objective is to delve into the evolving nature of individuals' music preferences over time. By understanding these changes, we aim to provide personalized music suggestions for individuals who share similar profiles. Furthermore, we plan to evaluate the effectiveness of content filtering criteria. Additionally, if time permits, we may explore the literary aspects of songs for recommendations. 

## Research questions
1. How do users' music phases evolve over time, and how can this information enhance music recommendations of people with similar profiles?
2. What are the most effective content filtering criteria for generating personalized music recommendations?
3. How can natural language processing techniques be utilized to extract and match literary components of songs for recommendation purposes? Is this effective as even if it works it is too much data to work with.

## Dataset
**[Spotify API](https://developer.spotify.com/documentation/web-api/reference/get-playlists-tracks):** We plan to extract user listening data to understand individual music preferences and phases over time.(We will try to extract it through API but since it isn’t easy we might use curated dataset in the end).

**Curated datasets:** [_Spotify Million Song Dataset_](https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset), we will use and compile a small dataset for initial testing and validation, with plans to utilize larger datasets for model training.

For the spotify dataset just looking at the data and through basic exploratory data analysis we observed that there are no missing values in it.We've decided to exclude links to songs as they hold no relevance, opting to retain the textual content for now. Moving on to Text Preprocessing, our initial steps involve removing special characters and punctuation marks, as well as converting all text to lowercase, excluding the common stopwords that contribute little to the overall context. Additionally, we can maybe transform the tokenized descriptions into numerical representations suitable for machine learning models.


## A tentative list of milestones for the project

_In the coming week we seek to achieve the following:_

1. Research and familiarization with Spotify API and relevant datasets.
2. Divide up the team tasks.
3. Data extraction and preprocessing.

And then we can go on with the development of filtering criteria and feature extraction models, model training and testing, user interface design and integration(not sure), documentation and finalization of the project.

## Documentation
This can be added as the project unfolds. You should describe, in particular, what your repo contains and how to reproduce your results.
