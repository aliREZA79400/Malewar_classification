# MaleWar Classification Project using Support Vector Classifier (SVC)

## Overview

This project is a small classification task that uses the Support Vector Classifier (SVC) algorithm from the Scikit-Learn library. The goal is to classify data into predefined categories after applying various data preprocessing techniques. The project is designed to be simple yet effective, demonstrating the importance of data preprocessing in machine learning tasks.

## Table of Contents

- [Dependencies](#dependencies)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Dependencies

The project requires the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

You can install these dependencies using pip:

```bash
pip install -r requirements.txt
```

## Data Preprocessing

The data preprocessing steps include:

1. **Handling Missing Values**: Imputation techniques are used to fill in missing values.
2. **Encoding Categorical Variables**: Categorical variables are encoded using techniques like One-Hot Encoding or Label Encoding.
3. **Feature Scaling**: Features are scaled to ensure that no single feature dominates the others.
4. **Feature Selection**: Relevant features are selected to improve model performance and reduce dimensionality.

The preprocessing steps are implemented in `src/preprocessing.py`.

## Model Training

The model used in this project is the Support Vector Classifier (SVC) from Scikit-Learn. The SVC is chosen for its robustness and ability to handle high-dimensional data. The model is trained on the preprocessed data using the following steps:

1. **Data Splitting**: The dataset is split into training and testing sets.
2. **Model Initialization**: The SVC model is initialized with appropriate hyperparameters.
3. **Model Training**: The model is trained on the training data.

The model training process is implemented in `src/model.py`.

## Evaluation

The model's performance is evaluated using the following metrics:

- **Accuracy**: The proportion of correctly classified instances.
- **Confusion Matrix**: A matrix showing the true vs. predicted labels.
- **Classification Report**: Precision, recall, and F1-score for each class.

The evaluation results are displayed in the terminal and can also be visualized using Matplotlib and Seaborn.

## Usage

To run the project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/classification_project.git
   cd classification_project
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```


