# Dogs vs Cats Image Classification using SVM

## Project Overview
This project implements a Support Vector Machine (SVM) machine learning algorithm to classify images of cats and dogs.

The model learns from image pixel features and predicts whether an image belongs to a cat or a dog class.

## Dataset
Dataset: Cats and Dogs Image Dataset (Kaggle)

Classes:
- 0 → Cat
- 1 → Dog

Total Images Used:
- 8005 images

Image Processing:
- Images resized to 64 × 64 pixels
- Images converted into numerical pixel features
- Features used for SVM classification

## Algorithm Used
### Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification problems. It finds the best decision boundary to separate different classes.

Kernel Used:
- Linear Kernel

## Project Workflow

1. Import required libraries
2. Load cat and dog images
3. Preprocess images
4. Convert images into NumPy arrays
5. Split data into training and testing sets
6. Train SVM classifier
7. Predict test images
8. Evaluate model performance

## Model Training

Training Data:
- 6404 images

Testing Data:
- 1601 images

Training Samples Used for SVM:
- 2000 images

## Model Performance

Accuracy:

52.03%

## Confusion Matrix

Confusion Matrix Result:

Explanation:

- 439 cats were correctly classified as cats
- 380 cats were incorrectly classified as dogs
- 388 dogs were incorrectly classified as cats
- 394 dogs were correctly classified as dogs

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- Support Vector Machine

## Files

## Conclusion

The project successfully implements an SVM classifier for cat and dog image classification. The model demonstrates how machine learning algorithms can be applied for image classification tasks.
