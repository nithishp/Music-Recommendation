# Music Recommendation Project

## Overview

This project is a music recommendation system that uses a decision tree algorithm to generate music genres based on user gender and age. It helps users discover music genres that match their preferences and provides recommendations accordingly.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Decision Tree Algorithm](#decision-tree-algorithm)

## Introduction

This project aims to enhance the user's music listening experience by providing genre recommendations based on two key factors: gender and age. By utilizing a decision tree algorithm, the system analyzes user input and suggests music genres that align with their preferences.

## Features

- Music genre recommendation based on user gender and age.
- Decision tree algorithm for personalized recommendations.
- User-friendly command-line interface.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/music-recommendation.git
   ```

2. Navigate to the project directory:

   ```bash
   cd music-recommendation
   ```

## Usage

To use the music recommendation system, follow these steps:

1. Ensure you have Jupyter Notebook installed.

2. Open the provided Jupyter Notebook file, `Music_Recommendation.ipynb`, in your Jupyter Notebook environment.

3. Run the notebook by executing the cells one by one.

4. When prompted, enter your gender and age.

5. The system will utilize the pre-trained joblib model to generate a music genre recommendation based on your input.

6. Enjoy listening to the recommended music!


## Data

The project uses a dataset containing information about various music genres, which is used to train the decision tree algorithm. The dataset is located in the `root` directory.

## Decision Tree Algorithm

The decision tree algorithm is used to make personalized music genre recommendations. It works by examining user input (gender and age) and traversing the decision tree to determine the recommended genre.


## Decision Tree Algorithm usage

The heart of this music recommendation system lies in the Decision Tree algorithm, which intelligently selects music genres based on user gender and age. Here's how it works:

1. **Data Collection and Preprocessing:** The algorithm starts by collecting a dataset that includes music genres and corresponding user profiles, with attributes like age and gender. This data is then preprocessed to ensure it's suitable for training the decision tree model.

2. **Training the Decision Tree Model:** A Decision Tree model is created using the preprocessed dataset. The model is designed to learn patterns and associations between user profiles (gender and age) and their preferred music genres. This learning process is crucial for making accurate genre recommendations.

3. **Feature Selection:** The model uses gender and age as features to make predictions. It evaluates these features to determine the best questions to ask during the decision-making process, ensuring the most relevant attributes are considered.

4. **Decision-Making Process:** When a user provides their gender and age, the Decision Tree model navigates through a series of decisions, much like a flowchart. It asks questions based on these attributes to narrow down the music genre recommendations. For instance, it may ask if the user is male or female, and then it will inquire about the user's age group.

5. **Recommendation Generation:** The algorithm reaches a leaf node in the decision tree, which corresponds to a specific music genre recommendation. The recommended genre is selected based on the user's input and the model's learned patterns.

6. **Personalized Recommendations:** The outcome is a personalized music genre recommendation tailored to the user's unique characteristics, making the listening experience more enjoyable and engaging.

7. **Model Persistence:** The trained Decision Tree model is serialized and stored as a joblib model, allowing for quick and efficient recommendations without the need for retraining every time.

This Decision Tree algorithm offers an efficient and user-centric approach to music recommendations, using gender and age as guiding factors to deliver a personalized music listening experience.
