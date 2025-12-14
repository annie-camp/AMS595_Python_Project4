# AMS595 Python Project 4

This repository contains my submission for **AMS 595 – Python Project 4**.  
The project explores optimization and regression techniques using NumPy and Matplotlib, culminating in binary image classification with logistic regression.

## Repository Contents

### Notebooks
- **AMS595_Py4_Parts2-4.ipynb**  
  Implements gradient descent, linear regression with two-dimensional features, and logistic regression on synthetic data.

- **AMS595_Py4_Part5_ORIGINAL.ipynb**  
  Re-implements a logistic regression classifier for the Cat vs. Non-Cat dataset using the original training and test split.  
  Includes identification and visualization of misclassified test images.

- **AMS595_Py4_Part5_MODIFIED.ipynb**  
  Re-trains the classifier using a modified training/test split derived from the original training set.  
  Reports training and test accuracy, misclassified indices, and includes a brief reflection on performance differences.

### Data
- `train_catvnoncat.h5` — training dataset  
- `test_catvnoncat.h5` — test dataset  

### Other Files
- `Py_Project_4_Instructions.ipynb` — project instructions  
- `README.md` — repository overview

## Use of AI Tools
AI tools (including **ChatGPT** and **Gemini**) were used to assist with **code formatting, debugging, clarification of concepts, and high-level organizational suggestions**.  
All implementations, analysis, and final decisions reflect my own understanding and work.

## Notes
All models are implemented **from scratch** using NumPy.  
No external machine learning libraries (e.g., scikit-learn, TensorFlow) are used.
