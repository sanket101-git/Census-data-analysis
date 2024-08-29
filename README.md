# Census-data-analysis

## Task 1: Exploratory Data Analysis (EDA)
Import CSV File:

Loaded the "census.csv" dataset containing 32,561 rows and 15 variables.
Data Description:

Target Variable: y represents income levels (<=50K or >50K).
The dataset consists of both numerical (e.g., age, fnlwgt) and categorical variables (e.g., workclass, education, marital.status).
Data Inspection:

Inspected data types and distributions using str(), summary(), and distinct levels in y.
Transformed certain variables into factors for modeling purposes.
Data Visualization:

Created visualizations, such as boxplots for age and hours.per.week by income level.
Used histograms for education.num and bar charts for workclass distribution.
Analyzed income levels by race and sex using a bar chart with facet_wrap.
Correlation Analysis:

Calculated a correlation matrix for numerical variables to understand their relationships.
## Task 2: Data Preparation
Scaling:

Performed log transformation on the fnlwgt variable to handle large ranges and improve model performance.
Encoding:

Categorical variables were converted into factors for easier handling in machine learning models.
Model Evaluation Metrics:

Identified key evaluation metrics: Accuracy, Precision, Recall, F1 Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), etc.
## Task 3: Model Building
C5.0 Decision Tree Model:

Built a C5.0 model using different CF levels.
Evaluated model performance on training and test datasets using confusion matrices and performance metrics.
Naïve Bayes and C5.0 with Cross Validation:

Implemented cross-validation using a custom function for performance evaluation.
Compared model metrics across multiple folds to gauge robustness and stability.
Other Algorithms:

Identified models suitable for classification tasks (C5.0, Naive Bayes, rpart, SVM) and unsupervised models that are not suitable (KMeans, Apriori).
## Task 4: Reflections
Reflecting on the performance of different models and their appropriateness for the task. Evaluating the effectiveness of your chosen algorithms and discussing potential improvements or alternative approaches could be part of this section.
