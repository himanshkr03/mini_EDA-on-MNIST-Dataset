# Exploratory Data Analysis (EDA) on the MNIST Dataset

## Overview

This project performs a comprehensive Exploratory Data Analysis (EDA) on the MNIST dataset, a collection of handwritten digits widely used for image recognition tasks. The analysis covers various aspects of the dataset, including basic information, visualization, pixel intensity analysis, mean images, correlation between digits, variance analysis, and feature importance using Principal Component Analysis (PCA).

## Dataset

The MNIST dataset is a built-in dataset in TensorFlow Keras. It consists of 70,000 grayscale images of handwritten digits (0-9), with 60,000 images for training and 10,000 images for testing. Each image is 28x28 pixels.

## Dependencies

The following libraries are required to run this project:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Scikit-learn

You can install these libraries using pip
## Analysis Steps

1. **Basic Dataset Information:**
   - Identifies the unique classes (digits 0-9) in the dataset.
   - Calculates the count of each label to understand the distribution of digits.
   - Visualizes the label distribution using a bar plot.

2. **Visualizing Sample Images:**
   - Displays a grid of 15 random images from the dataset to provide a visual understanding of the data.

3. **Analyzing Pixel Intensity:**
   - Normalizes pixel values to a range of 0 to 1 for statistical analysis.
   - Flattens the images into a 2D array for easier processing.
   - Plots the distribution of pixel intensity values using a histogram.

4. **Mean Images for Each Digit:**
   - Computes the mean image for each digit by averaging pixel values across all images of that digit.
   - Displays the mean images to visualize the typical representation of each digit.

5. **Correlation Between Digits:**
   - Calculates the pairwise correlation between the mean images of different digits.
   - Visualizes the correlation matrix using a heatmap to identify potential relationships between digits.

6. **Variance Analysis:**
   - Computes the pixel-wise variance for each digit to understand the variability within each class.
   - Displays the variance images to visualize areas of high and low variability.

7. **Feature Importance (Principal Component Analysis):**
   - Applies PCA to reduce the dimensionality of the data and identify the most important features.
   - Plots the 2D PCA representation of the data, color-coded by digit, to visualize clusters of digits.

## Conclusion

The EDA provides insights into the MNIST dataset, highlighting its balanced distribution, characteristic pixel intensity patterns, and relationships between digits. PCA helps to identify important features for further analysis, such as classification or clustering.

## Usage

To run the project:

1. Open the notebook in Google Colab.
2. Execute the code cells sequentially.
3. Observe the generated visualizations and outputs for each analysis step.
