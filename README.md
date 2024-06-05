# Iris Species Classification Project

## Project Overview
This project focuses on building and evaluating a machine learning model to classify Iris flowers into one of three species (Setosa, Versicolour, Virginica) based on their sepal and petal dimensions. The Iris dataset, a classic dataset in the machine learning community, has been used for this purpose.

## Dataset
The dataset contains 150 instances, each with four attributes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

There are three classes of Iris species:
- Iris Setosa
- Iris Versicolour
- Iris Virginica

## Methodology
- **Data Preprocessing**: The data is normalized to ensure consistent scale across all features.
- **Splitting Data**: The dataset is split into training and testing sets.
- **Model Training**: A K-Nearest Neighbors (KNN) classifier is used for training.
- **Model Evaluation**: The model is evaluated on the test set using metrics like accuracy, precision, recall, and F1-score.

## Results
- The model achieved an accuracy of 100% on the test set.
- Confusion Matrix:
  ```
  [[19  0  0]
   [ 0 13  0]
   [ 0  0 13]]
  ```
- Classification Report:
  - Precision, Recall, and F1-score of 1.00 for all classes.

## Requirements
- Python 3.x
- Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn

## Usage
1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to train the model and see the results.

## File Descriptions
- `Iris_Classification.ipynb`: Jupyter Notebook containing the code and analysis.
- `requirements.txt`: List of libraries required to run the project.

## Acknowledgements
- Dataset Source: UCI Machine Learning Repository - Iris Dataset
