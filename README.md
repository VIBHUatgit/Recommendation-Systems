# Recommendation Systems using Matrix Factorization and Neural Collaborative Filtering

## Table of Contents

- [Introduction](#introduction)
- [Concepts](#concepts)
  - [Content-Based Recommendation](#content-based-recommendation)
  - [Collaborative Filtering](#collaborative-filtering)
  - [Hybrid Recommendation Systems](#hybrid-recommendation-systems)
  - [Matrix Factorization](#matrix-factorization)
  - [Neural Collaborative Filtering](#neural-collaborative-filtering)
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction

This GitHub repository contains code and resources for building recommendation systems using two main techniques: Matrix Factorization and Neural Collaborative Filtering. Recommendation systems are essential in today's data-driven world, providing personalized suggestions to users based on their preferences and behavior. This project explores two popular approaches to recommendation systems and leverages the Surprise library and LightFM model for implementation.

## Concepts

### Content-Based Recommendation

Content-based recommendation systems make recommendations by analyzing the attributes or content of items and comparing them to a user's profile. These systems recommend items similar to those a user has previously shown interest in, based on features like keywords, genres, or item descriptions.

### Collaborative Filtering

Collaborative filtering recommendation systems make recommendations by leveraging the behavior and preferences of users. There are two main types:
- **User-Based Collaborative Filtering**: Recommends items to a user based on the preferences and behavior of users similar to them.
- **Item-Based Collaborative Filtering**: Recommends items to a user based on the similarity between items they have interacted with and items in the catalog.

### Hybrid Recommendation Systems

Hybrid recommendation systems combine multiple recommendation techniques, such as content-based and collaborative filtering, to provide more accurate and diverse recommendations. This project explores hybrid recommendations using matrix factorization and neural collaborative filtering.

### Matrix Factorization

Matrix Factorization is a technique used in collaborative filtering. It factorizes the user-item interaction matrix into lower-dimensional user and item matrices. The latent factors in these matrices capture user preferences and item characteristics. Matrix Factorization models are trained to predict missing values in the matrix, enabling personalized recommendations.

### Neural Collaborative Filtering

Neural Collaborative Filtering is an advanced recommendation technique that uses neural networks to capture complex patterns in user-item interactions. It combines the strengths of matrix factorization and neural networks to provide accurate recommendations. Neural Collaborative Filtering models can learn both linear and non-linear relationships in the data, making them highly effective for recommendation tasks.

## Project Overview

This project implements recommendation systems using Matrix Factorization and Neural Collaborative Filtering techniques. The Surprise library is used for matrix factorization, while the LightFM model is employed for neural collaborative filtering. The project explores the following:

- Data preprocessing and preparation.
- Matrix factorization-based recommendation using the Surprise library.
- Neural collaborative filtering using the LightFM model.
- Hybrid recommendation systems that combine both approaches for improved accuracy and diversity in recommendations.

## Dependencies

To run this project, you'll need the following dependencies:

- Python 3.x
- Surprise library (for matrix factorization)
- LightFM library (for neural collaborative filtering)
- Other required libraries (NumPy, SciPy, Pandas)

Install these dependencies by running:

```bash
pip install -r requirements.txt
```
## Results

The repository provides results and insights from experiments conducted using different approaches of Movie Recommendation Systems for Netflix Prize and Movielens Dataset. You can find details on model performance, accuracy, and other relevant metrics in the notebooks.

---

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, please feel free to contribute to the project. You can also open issues for bug reports or feature requests.

---

## Acknowledgements

This project draws inspiration and knowledge from various research papers, online resources, and open-source contributions.

Thank you for visiting my repository!
