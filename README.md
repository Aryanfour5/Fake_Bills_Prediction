# Fake Bills Detection Model

## Project Overview

This project develops a machine learning model to detect fake bills based on various features. The dataset includes features such as `diagonal`, `height_left`, `height_right`, `margin_low`, `margin_upper`, and `length`. We employ three different machine learning algorithms to achieve this: **k-Nearest Neighbors (k-NN)**, **Support Vector Machine (SVM)**, and **Logistic Regression**.

## Features

The dataset contains the following features:

- **`is_genuine`**: Boolean indicating whether the bill is genuine or fake.
- **`diagonal`**: Float representing the diagonal measurement of the bill.
- **`height_left`**: Float representing the height of the bill's left side.
- **`height_right`**: Float representing the height of the bill's right side.
- **`margin_low`**: Float representing the lower margin measurement of the bill.
- **`margin_upper`**: Float representing the upper margin measurement of the bill.
- **`length`**: Float representing the length of the bill.

## Algorithms Used

1. **k-Nearest Neighbors (k-NN)**
   - A non-parametric method used for classification that assigns a class based on the majority vote of its k-nearest neighbors.

2. **Support Vector Machine (SVM)**
   - A supervised learning model that finds the hyperplane that best separates classes in the feature space.

3. **Logistic Regression**
   - A linear model used for binary classification that estimates probabilities and applies a threshold to classify data.

## Installation

### Prerequisites

- Python 3.6 or higher
- Required Python libraries

### Installing Libraries

Clone the repository and install the required libraries:

