# Food Vision Project

This project is a food classification model built using TensorFlow and the Food101 dataset. The model is fine-tuned on EfficientNetV2 and trained to classify images of food into various categories. This project is part of a course requirement and demonstrates the application of deep learning in image classification.

## Project Overview

The goal of this project is to build an image classification model that accurately identifies different types of food from images. The Food101 dataset is used for training and evaluation, and the model utilizes mixed precision to optimize training speed and resource usage.

## Setup Instructions

1. Clone the repository and navigate to the project directory:

`git clone https://github.com/aiwkz/food-vision.git cd food-vision`\
`cd food-vision`

2. Install the necessary packages:

`pip install -r requirements.txt`

3. Download the helper functions script if not included:

`!wget https://raw.githubusercontent.com/aiwkz/food-vision/refs/heads/main/utils/helper_functions.py`

4. (Optional) If running in Google Colab, mount Google Drive to access the saved model.

## Usage

1. Run the notebook:

-   Open `food-vision.ipynb` in a Jupyter notebook environment or Google Colab.
-   Ensure you have access to the Food101 dataset through TensorFlow Datasets.

2. The notebook includes the following steps:

-   Loading and preparing the data.
-   Building and fine-tuning the EfficientNetV2 model.
-   Training and evaluating the model.
-   Saving and loading the model for reuse.

3. (Optional) Save the model in your Google Drive for future use.

## Requirements

-   Python 3.7+
-   TensorFlow 2.0+
-   TensorFlow Datasets
-   NumPy
-   Matplotlib

A `requirements.txt` file is included in the repository with the necessary dependencies.

## Results

The model achieved the expected accuracy on the Food101 dataset and is optimized for inference using mixed precision.

## Repository Structure

-   `food-vision.ipynb`: Main notebook containing code for data loading, model training, and evaluation.
-   `helper_functions.py`: Utility functions for data preprocessing and visualization.
-   `models/`: Directory where trained model files are saved.

## License

This project is created for educational purposes as part of a course and is not intended for commercial use.
