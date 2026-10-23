
# PyTorch Breast Cancer Classification

## About the Project
This project uses **PyTorch** to build a simple Artificial Neural Network (ANN) that classifies breast cancer data into two classes: malignant and benign.

The project demonstrates how a neural network learns from data and makes predictions using a training and evaluation process.

## Technologies Used
- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Google Colab

## Dataset
The project uses the Breast Cancer Wisconsin dataset available through Scikit-learn.

- **Input features:** 30
- **Classes:** Malignant (0) and Benign (1)
- **Task:** Binary classification

## Model Architecture
1. Input layer: 30 features
2. Hidden layer: 16 neurons with ReLU activation
3. Output layer: 1 neuron producing a logit

The model uses `BCEWithLogitsLoss` as its loss function and the Adam optimizer for training.

## How It Works
1. Load the dataset.
2. Split the data into training and testing sets.
3. Standardize the input features.
4. Convert the data into PyTorch tensors.
5. Create batches using `DataLoader`.
6. Train the neural network.
7. Evaluate the model using test accuracy.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. Review the training loss and test accuracy.

## Purpose
This is an educational machine learning project created to practice PyTorch, neural network training, and binary classification.

**Disclaimer:** This project is for educational purposes only and is not intended for medical diagnosis.
