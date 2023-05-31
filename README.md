# Mobile Price Category Prediction with HyperTuned ANN

This repository contains code for an Artificial Neural Network (ANN) model that has been hyperparameter tuned using Keras Tuner. The model is trained to predict the price category of a mobile device based on its specifications.

## Dataset

The mobile price category prediction model is trained on a labeled dataset of mobile device specifications and their corresponding price categories. The dataset includes features such as battery power, RAM, storage capacity, camera quality, and other relevant specifications. The dataset is provided in CSV format, with one row per mobile device and each column representing a feature or the target variable (price category).

Ensure that your CSV files follow the required format with labeled price categories and corresponding mobile specifications. Make sure to preprocess the data by performing necessary data cleaning, feature scaling, and splitting it into training and testing sets.

## Hyperparameter Tuning

Hyperparameter tuning is a crucial step in optimizing the performance of a machine learning model. In this repository, the ANN model is hyperparameter tuned using Keras Tuner. Keras Tuner allows for automated hyperparameter search, enabling the selection of the best combination of hyperparameters for the model. It explores different combinations of hyperparameters, such as the number of hidden layers, the number of neurons in each layer, the learning rate, and activation functions, to find the optimal configuration.

## Usage

To use the mobile price category prediction model, follow these steps:

1. Clone the repository:

```
git clone https://github.com/your-username/Mobile-Price-Category-Predictor.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Prepare your data:

   - Place your CSV files for training and testing in the `data` directory. Make sure you have separate CSV files for training and testing data.
   - Ensure that your CSV files have the necessary columns for features and the target variable (price category).
   - Perform data preprocessing, including data cleaning, feature scaling, and splitting the dataset into training and testing sets.

4. Run the Jupyter Notebook:

   - Open the Jupyter Notebook `Mobile_Price_Category_Prediction.ipynb` in your preferred environment (Jupyter Notebook, JupyterLab, Google Colab, etc.).
   - Update the notebook with the necessary paths to your training and testing data CSV files.
   - Run the notebook cell by cell, following the instructions and comments provided in the notebook.
   - The notebook will guide you through the hyperparameter tuning, training, evaluation, and prediction steps.

5. Making Predictions:

   - Use the trained model to make predictions on new mobile device specifications by executing the prediction code provided in the notebook.
   - Update the input data with the specifications of the mobile device you want to predict the price category for.
   - The notebook will preprocess the input data, load the trained model, and output the predicted price category.

## Contributing

Contributions to improve the mobile price category prediction model or extend it to handle other prediction tasks are welcome. If you encounter any issues or have suggestions, please open an issue or submit a pull request.


