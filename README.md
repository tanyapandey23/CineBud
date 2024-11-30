# CinePal 🎥

CinePal is a machine learning-powered movie recommendation system designed to help users discover new films based on their viewing history and preferences. Leveraging collaborative filtering, content-based filtering, and hybrid models, CinePal provides personalized movie suggestions tailored to each user's unique taste.

## Table of Contents

- [CinePal 🎥](#cinepal-)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Tech Stack](#tech-stack)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [Sample Output](#sample-output)

## Introduction

CinePal aims to enhance the movie-watching experience by offering intelligent movie recommendations. Whether you're into thrillers, rom-coms, or documentaries, CinePal learns from your past ratings and browsing behavior to suggest films that you'll love.

## Features

- **Personalized Recommendations**: Tailored movie suggestions based on user history and preferences.
- **Hybrid Recommendation System**: Combines collaborative filtering and content-based methods for more accurate predictions.
- **Search & Filter**: Quickly search for movies or filter recommendations by genre, release date, and more.
- **Scalable**: Capable of handling large datasets with millions of users and movies.
- **User Interface**: A simple and intuitive UI for easy interaction.

## Tech Stack

- **Python**: Core language for model development.
- **Pandas & NumPy**: Data manipulation and numerical computation.
- **Scikit-Learn**: Machine learning algorithms.
- **Streamlit**: Streamlit turns data scripts into shareable web apps
- **Pickle**: Pickle in Python is primarily used in serializing and deserializing a Python object structure.

## Installation

Follow these steps to set up CinePal locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/tanyapandey23/CinePal.git
    cd CinePal
    ```

2. **Install dependencies**:
    ```bash
    pip install pandas
    pip install numpy
    pip install --scikit-learn
    pip install pickle
    pip install streamlit
    pip install requests
    ```

4. **Set up the database**:
   - The dataset used in this project is from kaggle and can be found [here](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
   - Download the zip file and unarchive it in the same directory as the project.
####
5. **Run the jupyter script**
   Run the jupyter script file in the same directory as the project in order to make sure that the dataset has been established and working properly. and the project will be ready to run.
####
6. **Run the application**:
    ```bash
    streamlit run app.py
    ```

7. **Access the app**:
    Open your browser and go to `http://192.168.1.10:8501`.

## Usage

- **Browse Movies**: Check out the movies used by cinepal for your recommendations.
- **Browse Recommendations**: Check out the movies suggested by CinePal based on your ratings.

## Project Structure
The final project structure should look like
```plaintext
CinePal/
│
├── tmdb_5000_movies.csv                             # Dataset containing movie information
├── tmdb_5000_credits.csv                            # Dataset containing credits information
├── app.py                                           # main app file
├── movie_recommendation.ipynb                       # movie recommendation jupyter file
├── movie_dict.pkl                                   # pickle file
├── similarity.pkl                                   # pickle file
├── readme_images                                    # images for markdown file
│   ├── Screenshot%202024-08-17%20232836.png         #Screenshot 1
│   ├── Screenshot%202024-08-17%20232926.png         #Screenshot 2
│   ├── Screenshot%202024-08-17%20232938.png         #Screenshot 3
│   └── Screenshot%202024-08-17%20235251.png         #Screenshot 4

```
## Sample Output
![Alt text](readme_images/Screenshot%202024-08-17%20232836.png)

![Alt text](readme_images/Screenshot%202024-08-17%20232926.png)

![Alt text](readme_images/Screenshot%202024-08-17%20232938.png)

![Alt text](readme_images/Screenshot%202024-08-17%20235251.png)