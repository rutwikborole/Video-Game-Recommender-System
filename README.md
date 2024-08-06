# Video-Game-Recommender-System

Data: [Julian McAuley's Steam Video Game and Bundle Data](https://cseweb.ucsd.edu/~jmcauley/datasets.html#steam_data)
<h2>Description</h2>
Video Game Recommender System using  Neural Collaborative Filtering and Singular Value Decomposition


<h2>Languages and Utilities Used</h2>

- <b>Python
- Jupter Labs
- Keras
- TensorFLow


<h2>Environments Used </h2>

- <b>Windows 11</b> (21H2)

<h2>Program walk-through:</h2>

<p align="left">
This project explores the implementation and comparison of two collaborative filtering models, Neural Collaborative Filtering (NCF) and Singular Value Decomposition (SVD), for recommending games. The dataset includes user ratings for various games, along with metadata such as game titles and genres. The NCF model leverages deep learning techniques to learn complex user-item interactions, while the SVD model is a matrix factorization approach commonly used in recommendation systems.

Key features of the project include:

- Data Preprocessing: Mapping of user and game IDs, splitting the dataset into training, validation, and test sets, and handling missing values.
- Model Implementation: Construction and training of the NCF model using TensorFlow/Keras and the SVD model using the Surprise library.
- Evaluation Metrics: Calculation of RMSE, MAE, Recall@k, and HitRatio@k to evaluate model performance.
- Visualization: Plotting learning curves to analyze the training process and model performance over epochs.
<p> The project also includes an implementation of a recommendation system that generates top-k game recommendations for users. The results are visualized and compared to provide insights into the effectiveness of different models in capturing user preferences. This repository contains all the scripts, model checkpoints, and analysis required to reproduce the experiments and explore the dataset.
</p>
