# OIBSIP_TASK1
Iris Flower Classification
# Iris Flower Classification README

The Iris Flower Classification project aims to train a machine learning model to distinguish between three species of iris flowers: setosa, versicolor, and virginica. The model uses the measurements of the iris flowers to make accurate classifications.

## Dataset

To perform the Iris Flower Classification task,dataset is available in a CSV file named "Iris.csv". The dataset contains information about the sepal length, sepal width, petal length, petal width, and species of each iris flower.

## Libraries Used

The following Python libraries were used for this project:

- pandas: For data manipulation and analysis.
- numpy: For numerical operations.
- seaborn: For data visualization.
- matplotlib: For creating plots and visualizations.
- scikit-learn: For building and training machine learning models.

## Data Preprocessing

The initial step in the project involves importing the dataset using pandas and dropping the 'Id' column as it does not contribute to the classification. The data is then explored using functions like `head()`, `tail()`, and `describe()` to gain insights into its structure and summary statistics.

## Visualization

Data visualization is essential for understanding the relationships between different features and the target variable. The project uses various visualizations, such as pairplots and histograms, to explore the data and identify patterns or trends.

## Model Training

The project utilizes two machine learning algorithms for the classification task:

1. Logistic Regression: A popular algorithm for binary classification tasks.
2. Decision Tree Classifier: A powerful algorithm for both binary and multi-class classification tasks.

The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn. The models are then trained using the training data.

## Model Evaluation

To evaluate the performance of the trained models, the accuracy metric is used. The accuracy represents the percentage of correct predictions made by the models on the test data.

## Confusion Matrix and Classification Report

To gain a deeper understanding of the model's performance, confusion matrices and classification reports are generated for both Logistic Regression and Decision Tree models. The confusion matrix provides insights into the true positive, true negative, false positive, and false negative predictions. The classification report presents precision, recall, F1-score, and support for each class.

## Conclusion

The Iris Flower Classification project demonstrates the application of machine learning algorithms to accurately classify iris flowers based on their measurements. The combination of data preprocessing, visualization, model training, and evaluation provides a comprehensive understanding of the classification process.

The code provided in this README file can serve as a guide for implementing the project. Remember to adjust file paths and directory locations as needed when running the code locally. Happy coding and best of luck with your Iris Flower Classification project!
