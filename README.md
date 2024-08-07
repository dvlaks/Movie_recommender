# Movie Recommender System

![Screenshot1](Screenshot.png)
![Screenshot2](Screenshot2.png)

## Overview

This repository contains a Movie Recommender System built using machine learning techniques. The system suggests movies to users based on their preferences and past viewing history.It is a Movie Recommender System built using content-based filtering techniques. The system suggests movies to users based on the features of the movies they have previously enjoyed.

## Features

- **Collaborative Filtering:** Utilizes user-item interactions to recommend movies.
- **Content-Based Filtering:** Suggests movies based on movie features.
- **Hybrid Model:** Combines both collaborative and content-based filtering for better recommendations.

## Dataset

The dataset used for this project is stored in the `dataset` directory. It includes movie metadata and user ratings.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/dvlaks/Movie_recommender.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Movie_recommender
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter notebook:
    ```bash
    jupyter notebook movie_recommender.ipynb
    ```
2. Follow the steps in the notebook to train the model and generate recommendations.

## Files

- `movie_recommender.ipynb`: The main notebook containing the implementation of the recommender system.
- `movie_list.pkl`: Pickle file containing the list of movies.
- `similar.pkl`: Pickle file containing similarity data for the movies.
- `dataset/`: Directory containing the dataset files.
- `Screenshot1.png`, `Screenshot2.png`: Screenshots of the application.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements.
