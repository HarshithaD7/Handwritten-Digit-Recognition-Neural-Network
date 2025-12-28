Handwritten Digit Recognition using Neural Networks

Project Description

* This project implements handwritten digit recognition using a fully connected neural network built and executed in a Kaggle Notebook environment.
* The model classifies handwritten digits (0–9) using pixel-level image data, where each digit image is represented as 784 numerical features (28 × 28 pixels).
* The notebook covers the complete machine learning workflow including dataset loading, preprocessing, neural network training, evaluation, and prediction.

Objectives

* Load handwritten digit data provided in CSV format
* Perform preprocessing and normalization on pixel values
* Convert digit labels into one-hot encoded format
* Build and train a feedforward neural network
* Evaluate model performance using accuracy and loss
* Generate predictions for handwritten digit samples

Dataset

* Total training samples: 42,000
* Each sample consists of:
* 1 label column representing the digit (0–9)
* 784 pixel columns representing a 28 × 28 grayscale image
* Input feature shape after preprocessing: (42000, 784)
* Output label shape after encoding: (42000, 10)
* Due to GitHub file size limitations, only sample CSV files are included in this repository.
* The complete dataset was used directly within the Kaggle Notebook.

Notebook Execution Environment
* Platform: Kaggle Notebooks
* Language: Python
* Libraries used:
->NumPy
->Pandas
->Matplotlib
->Scikit-learn
->TensorFlow / Keras

All code execution, training, and evaluation are performed inside the Kaggle environment.

Workflow
Step 1: Data Loading
* The dataset is loaded from CSV files and inspected to understand its structure and dimensions.

Step 2: Data Preprocessing
* Pixel values are normalized to improve learning stability
* Feature columns are separated from target labels
* Labels are converted into one-hot encoded vectors

Step 3: Train–Validation Split
* The dataset is split into training and validation subsets to evaluate model generalization.

Step 4: Neural Network Model Construction
* A feedforward neural network is created using a Sequential architecture consisting of:
* Input layer for pixel values
* Two fully connected hidden layers with activation functions
* Output layer with softmax activation for multi-class classification

Step 5: Model Training
* The model is trained for 10 epochs
* Batch size used: 32
* Training accuracy and loss are monitored at each epoch
* Validation accuracy and loss are tracked to detect overfitting

Step 6: Model Evaluation
* After training, the model is evaluated on validation data to measure accuracy and loss.

Step 7: Predictions
* The trained model generates predictions for handwritten digit samples.
* Each prediction corresponds to the digit class (0–9) with the highest probability score.

Results:

* Training accuracy improved from 84.35% to 99.46% across epochs
* Best validation accuracy achieved: 97.25%
* Final validation accuracy: 97.07%
* Training loss decreased consistently, indicating effective learning
* Validation loss remained stable, showing good generalization
* The model correctly predicts handwritten digit classes for most samples
* Detailed outputs are available in the results/ directory
