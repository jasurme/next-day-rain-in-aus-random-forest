# WeatherAUS Dataset - My Project 
(you can download trained parameters)

## Overview

This is my personal project where I worked on predicting next-day rain using the **WeatherAUS** dataset. The goal was to predict whether it would rain the next day based on historical weather data. I used **Decision Trees** and **Random Forest** models to achieve the classification task, with the target variable `RainTomorrow`, which answers the crucial question: **Will it rain tomorrow?**

## Dataset Description

### Context

The goal of this dataset is to answer the question: **Will it rain tomorrow?** By using historical weather data, we can predict whether the rain threshold (1mm) will be exceeded.

### Target Variable

- **RainTomorrow**: This is the target variable I worked on predicting. It can have one of the following values:
  - `Yes`: Indicates that the rainfall for the next day was 1mm or more.
  - `No`: Indicates that the rainfall for the next day was less than 1mm.

### Features

The dataset contains various features, such as temperature, humidity, and wind speed, which I used to predict `RainTomorrow`. These features include:
- Temperature-related measurements (min, max, average)
- Humidity levels
- Wind speed and direction
- Rainfall on the given day
- Other meteorological features (e.g., cloud coverage, pressure)

### Data Format

The data is stored in CSV format with columns for each of the weather features and the target variable `RainTomorrow`. You can use it to train machine learning models for classification tasks.

## How I Used the Dataset

1. **Download and Preprocess**: First, I downloaded the dataset and cleaned the data by handling missing values and normalizing the features.
2. **Model Training**: I used **Decision Trees** and **Random Forest** classifiers to train the model. These models allowed me to predict the target variable `RainTomorrow` based on the weather features.
3. **Evaluation**: I evaluated the models based on their accuracy, precision, recall, and F1-score. The Random Forest model gave the best performance, outperforming Decision Trees in terms of generalization and prediction accuracy.

## Trained Parameters

For convenience, you can download the trained model parameters from Google Drive. This will allow you to skip the training step and directly apply the pre-trained model to make predictions on new data.

[**Download Trained Parameters**](https://drive.google.com/drive/folders/1BS2oGu2vhVV-XtLkAChpC-w1Iulb6A0G?usp=drive_link)

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- xgboost (optional, if using XGBoost for training)
- matplotlib (for visualizations)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
