Credit Card Fraud Detection

Overview
This project focuses on detecting fraudulent credit card transactions using data science and machine learning techniques. It involves data preprocessing, handling class imbalance, applying machine learning models, and visualizing results to improve fraud detection.

Key Features
Machine Learning Techniques: Implementation of classification models for fraud detection.
Class Imbalance Solutions: Applied ROS, RUS, and SMOTE for better dataset balancing.
Data Visualization: Insights into fraud patterns using R's visualization libraries.
Efficient Fraud Detection: Predict fraudulent transactions with increased accuracy.
Dataset
The dataset contains anonymized credit card transactions with 31 features.
Includes both legitimate and fraudulent transactions for analysis.
Publicly available at creditcard.csv.
Tools and Technologies
Programming Language: R
Environment: RStudio
Libraries Used: dplyr, caret, ggplot2, caTools, ROSE, smotefamily, rpart, rpart.plot
Implementation
Data Preprocessing: Cleaned and explored data, addressed missing values.
Sampling Techniques:
Random Over-Sampling (ROS): Duplicated minority class samples.
Random Under-Sampling (RUS): Reduced majority class samples.
SMOTE: Generated synthetic samples to balance classes.
Visualization: Pie charts and scatter plots for class distribution.
Modeling: Trained decision tree classifiers for fraud detection.
Challenges
Class Imbalance: Fraudulent transactions are rare, requiring effective balancing.
False Positives: Minimizing incorrect fraud flags to maintain efficiency.
How to Run
Clone the repository.
Install required R packages using install.packages().
Run the Credit-card-fraud-detection.R script in RStudio.
Explore the results and visualizations.
Results
Balanced the dataset using various sampling techniques.
Improved fraud detection accuracy using decision trees and SMOTE.
Author
Harpreet Singh
Connect with me on LinkedIn.

Feel free to let me know if you need further edits or additional sections for your README!
