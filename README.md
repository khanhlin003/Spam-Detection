# Welcome to spam-detection repository

## About 
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses Email Spam Detection from [Email Spam Classification Dataset](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv).

## Contributors
- @khanhlinh003
- @rayzheng59
- @AaronLim2001

## Problem Definition
- Are we able to predict whether an email is spam or not based on its content?
- Ways to resample imbalanced dataset?
- Which datasets perform well as training data?
- Which metrics are important in evaluating the models?
- Which model would be the best to predict spam emails?
- How to handle out of vocabulary words with the new dataset?

## Table of contents
1. Data extraction
2. Data resampling and splitting 
3. Data visualization
4. Decision Tree
5. Random Forest 
6. Naive Bayes

## Models Used
1. Decision Tree
2. Naive Bayes
3. Random Forest

## Conclusion
- False Positive Rate is significant in email spam detection as the classification of non-spam emails as spam can be an undesirable outcome
- Precision is also a good metric to look at as it takes into account the number of false positives
- F1 Score takes into account both Precision and Recall, which can be indicative of the balance between false positives and false negatives
- SMOTEENN was the worst performing training dataset in all 3 classifiers due to its high false positive rate
- SMOTETomek was the best performing training dataset in all 3 classifiers due to its low false positive rate
- Naive Bayes Classifier had the lowest number of false positives
- Both Decision Tree and Random Forest had the lower number of false negatives

## What did we learn from this project?
- Resampling of imbalanced dataset using Oversampling, Undersampling, SMOTEENN and SMOTETomek
- Decision Tree, Naive Bayes and Random Forest Classifier
- Incorporating existing models from sklearn
- Importance of Accuracy, Precision, Recall and F1 Score metrics
- Collaborating using GitHub

## References
- https://github.com/nicklimmm/movie-analysis
- https://www.kdnuggets.com/2020/07/spam-filter-python-naive-bayes-scratch.html
- https://towardsdatascience.com/accuracy-precision-recall-or-f1-331fb37c5cb9
- https://towardsdatascience.com/methods-for-dealing-with-imbalanced-data-5b761be45a18
