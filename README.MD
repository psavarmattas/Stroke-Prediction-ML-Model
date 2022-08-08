# Brain Stroke prediction- DecisionTree

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
2. https://www.kaggle.com (To download the dataset)
3. https://dreampuf.github.io/GraphvizOnline/ (To visualize the graph)

## Methodology:

1. IMPORTING LIBRARIES AND LOADING DATA
2. DATA EXPLORATION
3. VIZUALIZATION
4. DATA PREPROCESSING

    a. Target and Feature values / Train Test Split
5. MODEL BUILDING

    a. Decision Tree Classifier and Gini method

    b. Prediction Model File Generation

    c. Prediction Model File Loading

    d. Model accuracy score

        i. Testing Accuracy
        ii. Training Accuracy
6. MODEL WORKING GRAPH


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

### Vizualization

1. Cufflinks: It connects plotly with pandas to create charts directly on the dataframe.
2. go_offline: This enables us to use plotly offline rather than online.
3. offline=Flase: It enables the charts to not render locally.
4. df.groupby: It enables us to group dataframe using a mapper or a series of colomns.
5. df.values: It returns a numpy representation of the dataframe.
6. df.iplot: It is for building interactive plots.
7. df.sum: It returns a sum of values over the requested axis.

### Data Preprocessing

1. df.isnull: It detects missing values.
2. df.drop: It drops speficied labels from rows and columns.
3. get_dummies: It converts categorial variable into dummy/indicator variable.

### Model Building

1. criterion: The function to measure the quality of a split.
2. random_state: It controls the randomness of the estimator.
3. max_depth: The maximum depth of the tree.
4. clf_gini.fit: It is used to fit training data.
5. joblib.dump: It collects all the learning and dumps it in one file.
6. joblib.load: It reconstructs the file for use which is created by 'dump' method.
7. clf_gini.predict: It is a method which operates using numpy.argmax function on the output of predic_probo.
8. clf_gini.score: It returns the mean accuracy on the given test data and labels.
9. export_graphviz: It is used to export a decision tree in a '.dot' format.