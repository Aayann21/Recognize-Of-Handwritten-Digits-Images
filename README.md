# ✍️ Handwritten Digit Recognition

## Project Overview

This project recognizes **handwritten digits (0–9)** using a **Machine Learning classification model**. The model is trained on a dataset of handwritten digit images and learns to classify the digits correctly.

## Libraries Used

numpy
matplotlib
tensorflow.keras (mnist dataset)
sklearn.neural_network (MLPClassifier)
sklearn.metrics

## Dataset

The project uses the **Digits dataset**, which contains images of handwritten digits from **0 to 9**.
Each image is converted into numerical pixel values that are used to train the machine learning model.

## Features

* Pixel values of the handwritten digit images.

## Target Variable

* Digit labels **(0–9)** representing the handwritten number.

## Algorithm Used

**Classification Algorithm (Machine Learning Model)**

A classification model is used to identify and classify handwritten digits based on the pixel values of the images.

## Steps / Algorithm

1. Import required libraries.
2. Load the digits dataset.
3. Explore the dataset and visualize sample images.
4. Separate features (pixel values) and target labels (digits).
5. Split the dataset into **training and testing data**.
6. Train the machine learning classification model.
7. Predict the digit labels for test images.
8. Evaluate the model performance using accuracy score.
9. Display sample predictions and visualize results.

## Visualizations

The notebook includes visualizations such as:

* Displaying sample handwritten digit images
* Plotting predictions for test images
* Visualization of digit patterns using matplotlib

## Result

The trained model successfully classifies handwritten digits and predicts the correct digit labels for most test images.

## Conclusion

The project demonstrates how machine learning can be used to **recognize handwritten digits from image data**. The classification model learns patterns from pixel values and accurately predicts digits from **0 to 9**.

---
