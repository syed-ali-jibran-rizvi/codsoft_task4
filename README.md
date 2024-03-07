# Music Recommender System

This project is a simple music recommender system that suggests similar songs based on a selected song. It uses a dataset of song lyrics to calculate similarity between songs and recommends songs with similar lyrics.

## Features

- Recommends similar songs based on the selected song.
- Retrieves album cover URLs for recommended songs using the Spotify API.

## Installation

1. Clone the repository:

    ```
    git clone https://https://github.com/syed-ali-jibran-rizvi/codsoft_task4
    ```

2. Obtain Spotify API credentials:
    - Create a Spotify Developer account and create a new application.
    - Note down the Client ID and Client Secret.

3. Update the `app.py` file with your Spotify API credentials.

## Usage

1. Run the `app.py` script:

    ```
    python app.py
    ```

2. Follow the on-screen instructions to select a song from the list of available songs.
3. The program will recommend similar songs and display their album cover URLs.

## Dataset

The dataset used in this project contains song lyrics sourced from https://www.kaggle.com/datasets/notshrirang/spotify-million-song-dataset. It is used to calculate similarity between songs for recommendation.

## Credits

- Kaggle for its dataset
- [Spotipy](https://spotipy.readthedocs.io/) - Python library for the Spotify Web API.

