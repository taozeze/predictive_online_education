# Predictive modeling on churning from online course using Python Scikit-learn and Keras

Summary: this project analyzes which student will churn (i.e. withdraw during the course or get fail at the end of course) from online course, using data from student demographic, assessment performance and interaction with online platform. Random forest, XGBoost and Neural Network are built to predict the probability of being withdrawn or fail, and cumulative gain charts are generated to understand the percentage of positives correctly classified, as a function of the percentage of the population that is targeted. Business users can utilize the result to decide how many % of students to target for early intervention. 

Highlight:
1) Dynamic prediction: can specify how many days to predict forward for withdrawal case
2) Algorithm selection: use both Random Forest and XGBoost to achieve high accuracy, and also understand the feature importance
3) Evaluation metric: use cumulative gain chart and KS statistic to evaluate model and provide actionable suggestions for business people. 

Dataset: Open University Learning Analytics dataset (https://analyse.kmi.open.ac.uk/open_dataset)

Tool and Package: Python - Pandas, Scikit-learn, Keras and Scikitplot (a newly launched package that can generate different model evaluation charts, super helpful!)

