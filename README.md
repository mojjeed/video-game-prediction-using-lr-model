# video-game-prediction-using-lr-model
# VGChartz Sales Analysis and Prediction

This project aims to analyze and visualize video game sales data from VGChartz and build a linear regression model to predict future sales. The dataset contains various attributes related to video games, including sales data in different regions, critic scores, genres, and release dates.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Visualizations](#visualizations)
- [Model](#model)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to gain insights into video game sales trends and build a model that can predict future sales based on historical data.

## Data

The dataset used in this project is a CSV file named `vgchartz-2024.csv`. It contains the following columns:

- `title`: The title of the game.
- `genre`: The genre of the game.
- `critic_score`: The critic score of the game.
- `na_sales`: Sales in North America (in millions).
- `jp_sales`: Sales in Japan (in millions).
- `pal_sales`: Sales in Europe (in millions).
- `other_sales`: Sales in other regions (in millions).
- `total_sales`: Total sales worldwide (in millions).
- `release_date`: The release date of the game.

## Visualizations

The project includes the following visualizations:

1. **Total Sales Distribution**: A histogram showing the distribution of total sales across all games.
2. **Sales by Region**: A bar plot comparing sales in North America, Japan, Europe, and other regions.
3. **Top 10 Games by Total Sales**: A bar plot showing the top 10 games with the highest total sales.
4. **Genre Distribution**: A pie chart displaying the distribution of games across different genres.
5. **Critic Scores Distribution**: A histogram showing the distribution of critic scores for the games.
6. **Total Sales Over Time**: A line plot illustrating how total sales have changed over time.

## Model

A linear regression model is built to predict the total sales of a game based on the following features:

- `critic_score`
- `na_sales`
- `jp_sales`
- `pal_sales`
- `other_sales`
- `release_year`
- `release_month`

The data is preprocessed by filling missing values with 0 and splitting it into training and testing sets.

## Evaluation

The model is evaluated using the Mean Squared Error (MSE) and R-squared (R²) score. The results are as follows:

- **Mean Squared Error (MSE)**: 2.35e-05
- **R-squared (R²) score**: 0.99997

These metrics indicate that the model has a very high accuracy in predicting total sales.


