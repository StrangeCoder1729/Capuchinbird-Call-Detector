# Capuchinbird Call Detector

This project aims to build an audio classifier using TensorFlow to detect Capuchinbird calls from audio recordings. The key steps include:

1. **Installation**: Installing necessary libraries like TensorFlow, TensorFlow-IO, and Matplotlib.
2. **Data Preparation**: Loading audio files, preprocessing them by resampling to 16kHz, and converting them to spectrograms.
3. **Model Training**: Creating and training a Convolutional Neural Network (CNN) on labeled audio data of Capuchinbird calls and other sounds.
4. **Prediction on New Data**: Applying the trained model to new audio recordings to detect Capuchinbird calls, using a sliding window approach to handle long recordings.
5. **Export Results**: Aggregating the model predictions and exporting the results to a CSV file.

## Table of Contents

1. [Installation](#installation)
2. [Data Preparation](#data-preparation)
3. [Model Training](#model-training)
4. [Prediction on New Data](#prediction-on-new-data)
5. [Export Results](#export-results)
6. [Credits](#credits)
7. [License](#license)

## Installation

Install required libraries:

```bash
pip install tensorflow==2.8.0 tensorflow-io==0.25.0 matplotlib
```

## Data Preparation

Load and preprocess audio files, converting them to a standard format suitable for model training.

## Model Training

Train a CNN on the preprocessed audio data to classify Capuchinbird calls.

## Prediction on New Data

Use the trained model to detect Capuchinbird calls in new audio recordings and post-process the results to identify distinct calls.

## Export Results

Export the final detection results to a CSV file for analysis.

## Credits

This project is based on the tutorial by Nick Nochnack. For more information, visit [Nick Nochnack's GitHub](https://github.com/nicknochnack).

 
