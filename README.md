# Iris Dataset Classification Project

## Project Overview
<p style="text-align: justify"> 
This project focuses on the classification of the Iris plant species using the well-known Iris dataset. The Iris dataset is a classic in the pattern recognition literature and has been frequently referenced in scientific studies. The dataset consists of 150 instances, representing three different classes of Iris plants. One of these classes is linearly separable from the other two, while the other two classes are not linearly separable from each other.
</p>

## Dataset Information

### Context

The Iris dataset contains three classes of 50 instances each, representing three species of Iris plants:
- Iris Setosa
- Iris Versicolour
- Iris Virginica


Each instance in the dataset has four features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The goal of this project is to predict the class of Iris plant based on these features.

Dataset Source
- [Click here to access the dataset](https://archive.ics.uci.edu/dataset/53/iris)

## Project Tasks
The tasks for this project are divided into several key steps:

1. Exploratory Data Analysis (EDA)
    - Perform EDA to explore the features of the Iris dataset.
    - Visualize the distribution of features using histograms.

2. Target Variable Encoding
    - Encode the target variable (Iris species) by converting it into numeric form for machine learning models.

3. Data Splitting and Experimentation
    - Experiment with two different ratios of training, validation, and test data:
    - 60-20-20 (60% training, 20% validation, 20% test)
    - 80-10-10 (80% training, 10% validation, 10% test)

4. Model Implementation
    - KFold Cross Validation: Implement KFold cross-validation to assess model stability.
    - Grid Search: Use GridSearchCV to find the optimal hyperparameters for any three algorithms out of the following:
        - Logistic Regression (LR)
        - Support Vector Machine (SVM)
        - Multi-Layer Perceptron (MLP)
        - Random Forest (RF)
        - Boosting (e.g., Gradient Boosting, AdaBoost)
5. Model Evaluation
    - Analyze the results on the validation and test sets to determine which model performed the best and why.
    - Compare the performance of models using evaluation metrics such as precision, recall, accuracy, and latency.
6. Best Proportion Analysis
    - Based on the experiments, determine which proportion or split ratio (60-20-20 or 80-10-10) provided the best model performance.

## Conclusion
<p style="text-align: justify">
This project aims to thoroughly explore the Iris dataset, experiment with different machine learning algorithms, and determine the best model and data split ratio for accurately classifying the Iris plant species. Through this process, you will gain insights into the relationship between model performance and data distribution, as well as the effectiveness of different machine learning techniques on this classic dataset.
</p>


