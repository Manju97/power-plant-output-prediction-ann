# Power Plant Output Prediction Using an ANN

A mini project that uses an Artificial Neural Network (ANN) to predict
power plant output from the available dataset features. The model is built
with PyTorch and evaluated using regression metrics.

## Project overview

This project explores how a neural network can learn relationships between
power plant data and its output. The notebook covers data preparation,
model training, and evaluation on training and test data.

## Dataset

- **Dataset:** powerplant_data.csv
- **Prediction target:** PE
- **Input features:** AT,V,AP,RH,PE

> Add the dataset to the project only if its license permits redistribution.
> Otherwise, include instructions or a link for obtaining it.

## Model and evaluation

The model is implemented in PyTorch and trained for a regression task using
the Adam optimizer and Mean Squared Error (MSE) loss.

Reported test-set R² score: **0.938**

The notebook also calculates training and testing MSE. Results may vary if
the data split, preprocessing, or model settings change.

## Repository contents

- `ANN_Regression.ipynb` — notebook containing the model workflow
- `data/` — dataset files, if included and permitted

