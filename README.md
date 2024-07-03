# Stock Price Prediction using LSTM

This repository contains a project focused on predicting stock prices using Long Short-Term Memory (LSTM) networks. The project demonstrates how to preprocess stock market data, build and train an LSTM model, and evaluate its performance.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The goal of this project is to predict the future prices of the preferred stock using LSTM networks. The project covers data collection, preprocessing, model building, training, and evaluation.

## Dataset

The dataset used in this project is obtained from Yahoo Finance and contains historical stock prices for the preferred stock. 

## Preprocessing

The preprocessing steps include:
- Scaling the data using MinMaxScaler to normalize the feature values.
- Creating sequences of time steps to be used as input for the LSTM model.
- Splitting the data into training and test sets.

## Model Architecture

The LSTM model is built using the Keras library and consists of the following layers:
- Three LSTM layers with 20 units each, the first two layers return sequences.
- A Dense layer for the final output.

