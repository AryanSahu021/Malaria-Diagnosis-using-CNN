# Malaria Diagnosis using Convolutional Neural Networks (CNN)

This project focuses on diagnosing malaria using Convolutional Neural Networks (CNNs). The dataset used for training and testing is TensorFlow's malaria dataset, which contains cell images infected with malaria parasites and uninfected cell images.

## Dataset
The dataset used in this project is available in TensorFlow's dataset library. It consists of thousands of cell images infected with malaria parasites and an equal number of uninfected cell images. This dataset serves as the input for training and testing our CNN model.

## Requirements
- Python 3.x
- TensorFlow
- Matplotlib
- NumPy


## Usage
1. Download the TensorFlow malaria dataset or load it directly from TensorFlow's dataset library.
2. Preprocess the data, which may include resizing images, normalization, and splitting into training and testing sets.
3. Train the CNN model using the provided Python scripts or Jupyter Notebooks.
4. Evaluate the trained model on the test dataset to assess its performance.
5. Fine-tune the model parameters or architecture as needed for better results.

## Model Architecture
The model architecture consists of multiple convolutional layers followed by fully connected layers. The CNN layers extract features from input images, and the fully connected layers classify these features to determine whether a cell is infected with malaria or not.

## Evaluation
The performance of the model is evaluated using binary cross-entropy loss and accuracy metrics. The loss function measures the difference between predicted and actual labels, while accuracy indicates the model's ability to correctly classify infected and uninfected cells.

## Results
After training and testing the model, the following results were obtained on the test dataset:
- Loss: 0.2014
- Accuracy: 0.9387

