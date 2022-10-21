# Brain Stroke prediction- DecisionTree
`Last Updated: 21th October 2022`

A stroke is an interruption of the blood supply to any part of the brain. If blood flow was stopped for longer than a few seconds and the brain cannot get blood and oxygen, brain cells can die, and the abilities controlled by that area of the brain are lost. In this Notebook we will use some features to see wether we will be able to predict the stoke or not? This is just a theoretical Machine Learning Model that will analyze the data and determine where the stroke can occur.

## Basic Outline For A Machine Learning Model:

Points to keep in mind when working with a machine learning model

1. Import the Data
2. Clean the Data
3. Split the Data into Training/Test Sets
4. Create Model
5. Train the Model
6. Make Predictions
7. Evaluate and Improve

## Libraries Needed:

1. Numpy
2. Pandas
3. Matplotlib
4. Scikit-Learn
5. Seaborn
6. Cufflinks

## Tools Needed:

1. Jupyter (IDE)
2. Github (To pull repository)

## Installation Instructions:

1. Clone the repository.
2. Open terminal and 'cd' to the directory where to saved the repository.
3. Run the command `pip install -r requirements.txt`.
4. Now start working on the repository.

## Methodology:

1. IMPORTING LIBRARIES AND LOADING DATA
2. DATA EXPLORATION
3. DATA PREPROCESSING

    a. Target and Feature values / Train Test Split
4. MODEL BUILDING

    a. KNeighborsClassifier

    b. Support Vector Classification (SVC)

    c. Decision Tree Classifier

    d. Random Forest Classifier

    e. Multi-layer Perceptron classifier

    f. Stacking Classifier

5. Prediction Testing


## In-Depth Working of this model:

### Imports

1. Numpy: For working with arrays.
2. Pandas: Used to analyze the data.
3. OS Module: For working with files/directories.
4. matplotlib: Used for programmatic plot generation.
5. Seaborn: Used for statistical graphics.
6. Warnings: Used to control warnings in Python.
7. sklearn: These are simple and efficient tools for predictive data analsis.

### Data Exploration

1. pd.read_csv: Used to load cvs files in pandas dataframe.
2. df.head: It returns first 'n' rows.
3. pd.info: It prints information about the dataframe.
4. df.describe: It generates descriptive statistics.
5. unique: It returns unique values from the dataframe.

### Data Preprocessing

1. df.isnull: It detects missing values.
2. df.drop: It drops speficied labels from rows and columns.
3. get_dummies: It converts categorial variable into dummy/indicator variable.
4. df.dropna: It drops coloumns and rows where null value is present.

### Model Building

1. KNeighborsClassifier: Classifier implementing the k-nearest neighbors vote.
2. Support Vector Classification (SVC): SVC is class capable of performing binary and multi-class classification on a dataset.
3. Decision Tree Classifier: Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.
4. Random Forest Classifier: A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree.
5. Multi-layer Perceptron classifier: This model optimizes the log-loss function using LBFGS or stochastic gradient descent.
6. Stacking Classifier: Stacked generalization consists in stacking the output of individual estimator and use a classifier to compute the final prediction. Stacking allows to use the strength of each individual estimator by using their output as input of a final estimator.
7.. joblib.dump: It collects all the learning and dumps it in one file.
8. joblib.load: It reconstructs the file for use which is created by 'dump' method.

## Prediction Testing

1. random: It generates random output.