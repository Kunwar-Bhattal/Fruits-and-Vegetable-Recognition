# Fruit and Vegetable Image Classifier

## Overview
This project aims to classify images of fruits and vegetables into 36 different categories. It utilizes deep learning techniques with TensorFlow and Python. The model is trained on a dataset containing labeled images of various fruits and vegetables.

## Project Structure
- `JupyterNotebook/`: Contains the notebooks ImageRecognition.ipynb which prprocesses the Data and creates the model. Testing_ImageRecognition.ipynb contains code to test the model and view the Results and statistics.
- `trained_model_Recognition.h5`: This is the model stored in h5 file format.
- `training_hist.json`: It can be used to visualize the model in histogram format.
- 'requirments': The requirments to acces the project are listed in Readme.md file in main branch.

## Usage
1. Prepare your dataset:
   - Collect labeled images of fruits and vegetables.
   - Organize them into subfolders (one per class) within the `data/` directory.

2. Data Preprocessing:
   - Resize images to a consistent size (e.g., 64x64 pixels).
   - Normalize pixel values (0-255) to the range [0, 1].

## Results
- The model's performance has been evaluated using validation data.
- Loss- 1.253, Accuracy-80.6%, Validation Accuracy- 87.46%.

## Visualization
- Create visualizations using Matplotlib:
  - Confusion matrix
  - Sample images with predicted labels

## Future Improvements
- Experiment with different architectures (e.g., transfer learning with pre-trained models).
- Augment the dataset with more diverse images.
- Optimize hyperparameters for better performance.

## Acknowledgments
- The Libraries used in the project are: Numpy, MatplotLib and Tensorflow.
- The dataset for training and validation was imported from "kritikseth/fruit-and-vegetable-image-recognition" on Kaggle.
