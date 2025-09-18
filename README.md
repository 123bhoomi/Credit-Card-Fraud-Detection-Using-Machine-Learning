# Credit-Card-Fraud-Detection-Using-Machine-Learning
Built and evaluated machine learning models on the Credit Card Fraud Detection dataset, applying preprocessing, EDA, and feature engineering to improve fraud identification, with performance validated through precision, recall, F1, and AUC-ROC metrics.

Task 1:
Data Cleaning, Preprocessing And EDA:
1.Check for and handle any missing/null values.
2.Scale the Amount column.
3.Convert Time to derived feature with the formula Transaction Hour = FLOOR(Time / 3600).
4.Check Class balance (count of fraud vs. non-fraud).

Task 2:
Exploratory Data Analysis (EDA):
1.Distribution of Amount for fraud VS non-fraud.
2.Count of fraud and non-fraud transactions.
3.Correlation heatmap of V1–V28 with Class.
4.Time-of-day patterns in fraud.
5.Boxplots of selected features by fraud label.

Task 3:
Feature Engineering:
1.Create a Transaction Hour from Time.
2.Log-transform Amount to reduce skewness.
3.Create a binary flag for High Amount transactions. Take a flag accordingly.
4.PCA/Dimensionality Reduction: Visualize separability of classes.

Task 4:
Modeling:
1.Split the dataset into training and test sets.
2.Train at least 3 classification models.
3.Use class_weight='balanced' or sampling to address imbalance.

Task 5:
Model Testing And Evaluation:
1.Evaluate models using Accuracy, Precision, Recall, F1-Score and AUC-ROC.
2.Use a confusion matrix to analyze false positives and false negatives.
3.Plot ROC curves for all models.

