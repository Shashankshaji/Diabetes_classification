# Diabetes_classification
Here I am using diabetes dataset. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.
# Tools Used
**Python**
- Python is an interpreted, object-oriented, high -level programming language with dynamic semantics.
- Python V3.9 is the latest.

**Google Colab**
- Colaboratory or “Colab” for short, is a product from Google Research. Colab allows anybody to write and execute python code through the browser like Jupyter notebook, well suited to ML, data analysis etc. 
- Google colab can be accessed by going to any browser and searching “https://research.google.com/colaboratory/”
- In Google colab we use libraries like pandas, matplotlib and sklearn

**Sklearn**
- Scikit-learn is a free software machine learning library for the Python programming language.
- Sklearn library contains a lot of efficient tools for ML, modelling, classification, regression etc.

**Pandas**
- Pandas is a Python package providing fast, flexible, and expressive data structures designed to make working with “relational” or “labelled” data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real-world data analysis in Python.

# ALGORITHM USED
**SVM (Support Vector Machine)**
- A support vector machine (svm) is a supervised machine learning model that uses classification algorithms for two-group classification problems. after giving a svm model sets of labelled training data for each category, they're able to categorize new text.

**Logistic Regression**
- Logistic regression is a statistical analysis method used to predict a data value based on prior observations of a data set. Logistic regression has become an important tool in the discipline of machine learning. The approach allows an algorithm being used in a machine learning application to classify incoming data based on historical data. As more relevant data comes in, the algorithm should get better at predicting classifications within data sets.

**KNN**
- K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.
- K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.

**Decision Tree**
- Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving regression and classification problems too.
-The goal of using a Decision Tree is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data(training data).


# Conclusion
- Using Knn we got 76% accuracy and by  using Decision Tree we got 75% accuracy.
- By using SVM we got 85% accuracy using linear kernel and using rbf kernel we got 84% accuracy.
- By using Logistic Regression, we got 85% accuracy.
- Our team has come to a conclusion that for this dataset Logistic Regression and SVM is more suitable as it is more accurate.
