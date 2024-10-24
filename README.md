
# K-Nearest Neighbors (KNN) Model - Crop Prediction

## Overview
This project implements a K-Nearest Neighbors (KNN) classification algorithm to predict the type of crop based on various environmental and soil factors. The model is trained using data that includes features like nitrogen (N), phosphorus (P), potassium (K), temperature, humidity, pH level, and rainfall.

## Dataset
The dataset includes the following features:
- **N (Nitrogen)**: Nitrogen content in the soil
- **P (Phosphorus)**: Phosphorus content in the soil
- **K (Potassium)**: Potassium content in the soil
- **Temperature**: Atmospheric temperature
- **Humidity**: Atmospheric humidity
- **pH**: pH level of the soil
- **Rainfall**: Amount of rainfall in the area
- **Label**: The type of crop (e.g., rice)

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Vmgsankar/K-Nearest-Neighbors-KNN-ML
    ```

## Usage
To run the KNN model and make predictions:
1. Load the dataset.
2. Preprocess the data.
3. Split the dataset into training and test sets.
4. Train the KNN model using the training set.
5. Evaluate the model on the test set.
6. Make predictions based on the environmental and soil parameters.


## Conclusion
The KNN model was able to classify different crops based on their environmental and soil conditions with a reasonable level of accuracy. Further tuning of hyperparameters like the number of neighbors could improve the model's performance.
