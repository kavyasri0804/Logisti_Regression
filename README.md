# Iris Flower Classification Using Logistic Regression

## 📌 Project Overview
This project uses the **Logistic Regression** machine learning algorithm to classify Iris flowers into three species: Iris Setosa, Iris Versicolor, and Iris Virginica. The model uses flower measurements to predict the species.

## 🎯 Objectives
- Load and preprocess the Iris dataset.
- Convert flower species labels into numerical values.
- Split the dataset into training and testing sets.
- Train a Logistic Regression classification model.
- Evaluate model performance using classification metrics.
- Predict the species of a new flower.
- Save and load the trained model using Pickle.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Pickle

## 📂 Dataset
The project uses the Iris dataset, which contains measurements of three Iris flower species.

### Input Features
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes
- Iris Setosa
- Iris Versicolor
- Iris Virginica

## ⚙️ Project Workflow
1. Load the dataset from `iris.csv`.
2. Remove the unnecessary `Id` column.
3. Convert the species names into numerical labels.
4. Separate input features and the target variable.
5. Split the dataset into 80% training data and 20% testing data.
6. Train the Logistic Regression model.
7. Evaluate training and testing performance.
8. Predict the species for a custom input.
9. Save the trained model as a Pickle file and load it again for prediction.

## 🧠 Algorithm: Logistic Regression
Logistic Regression is a supervised machine learning algorithm used for classification problems. It estimates the probability that an input belongs to a particular class and assigns the most suitable class.

In this project, Logistic Regression predicts the Iris flower species based on four measurements.

## 📊 Model Evaluation
The model is evaluated using the following metrics:

- **Accuracy Score:** Measures the proportion of correct predictions.
- **Confusion Matrix:** Compares actual and predicted class labels.
- **Classification Report:** Displays precision, recall, F1-score, and support for each class.

The training and testing evaluation results are displayed when the program runs.

## 💾 Model Saving and Loading
The trained model is saved as `Iris_Model_LR.pkl` using Python's Pickle module. The saved model is then loaded and used to make predictions.

**Security Note:** Only load Pickle files from trusted sources.

## 📦 Installation
Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## ▶️ How to Run the Project
1. Clone or download the repository.
2. Place `iris.csv` in the same directory as `logistic_regression.py`.
3. Open a terminal in the project directory.
4. Run the following command:

```bash
python logistic_regression.py
```

The program displays the model evaluation results and predicts the Iris flower species for a sample input.

## 🚀 Future Enhancements
- Compare Logistic Regression with other classification algorithms.
- Visualize the dataset and model performance.
- Apply feature scaling and cross-validation.
- Develop a web application for interactive flower classification.

## 📝 Conclusion
This project demonstrates the application of Logistic Regression to a multiclass classification problem using Python and Scikit-learn. It covers data preprocessing, model training, evaluation, prediction, and model persistence.
