This notebook presents a comparative study between two popular machine learning models—Random Forest (RF) and Convolutional Neural Networks (CNN)—in the context of image classification using Histogram of Oriented Gradients (HOG) features. The analysis employs 5-fold cross-validation to assess the performance of these models, ensuring robustness and generalizability.

Key Topics Covered:

Understanding HOG Features:
How HOG extracts edge and texture information for object detection.
Preprocessing techniques including grayscale conversion, gamma correction, and image resizing.
Dataset Preparation:
Loading and preprocessing image data using OpenCV and scikit-image.
Labeling images based on predefined categories (e.g., smoking vs. non-smoking).
Model Comparison:
Implementing Random Forest (RF) as a traditional machine learning approach.
Using Convolutional Neural Networks (CNN) for deep learning-based classification.
Evaluating both models using 5-fold cross-validation.
Performance Metrics:
Accuracy, precision, recall, and F1-score comparisons.
Visualization of results using matplotlib and seaborn.
Objective:
The primary goal is to determine which model—RF or CNN—performs better for the given image classification task when using HOG-based feature extraction.
