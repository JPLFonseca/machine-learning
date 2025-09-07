

***

### Machine Learning

# Pima Indians Diabetes Prediction

This project focuses on developing a binary classification model to predict the onset of diabetes in patients from the **Pima Indians Diabetes Dataset**. The dataset includes information on 768 women, with 8 medical and personal characteristics.

### Objectives

* Develop a **binary classification model** to predict diabetes.
* Explore and compare the performance of at least three binary classifiers, including a **RandomForestClassifier**.
* Analyze the impact of **data normalization** on model performance.
* Use appropriate metrics and methodologies for training and evaluation to ensure reliable performance estimation.

### Models Used

The project evaluates three binary classifiers:

* **Support Vector Machine (SVM):** An algorithm that finds an optimal separating hyperplane to classify data.
* **Linear Regression:** An algorithm used to find a linear relationship between input and a continuous output variable.
* **Random Forest Classifier:** A supervised learning algorithm that combines multiple decision trees to improve classification accuracy and reduce overfitting.

***


# IMDb Movie Review Classification

This project focuses on **sentiment analysis** and **text classification** using a dataset of 50,000 movie reviews from the Internet Movie Database (IMDb). The goal is to predict the review's score, which ranges from 1 to 10 (neutral scores of 5 and 6 are excluded).

### Objectives

* **Multi-class Classification:** Train a classifier to predict the review score.
* **Regression:** Train a regressor to predict the review score.
* **Clustering:** Use unsupervised methods to group reviews and identify common topics.

### Methodology

The approach involves:

* **Vocabulary Construction:** Cleaning the text and using techniques like `TfidfVectorizer` to build a representative vocabulary.
* **Modeling:** The same vocabulary is used for both classification and regression tasks.
* **Performance Evaluation:** A suitable test methodology and performance metrics are used to ensure the reliability of the trained models.
