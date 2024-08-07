# ENCRYPTIX
Task 1 : Titanic survival prediction
Data Preparation
Loading the Dataset: The Titanic dataset is loaded into a Pandas DataFrame.
Dropping Unnecessary Columns: Columns PassengerId, Name, Ticket, and Cabin are removed as they are not useful for the prediction.
Handling Missing Values:
The Age column's missing values are filled using the median age.
The Embarked column's missing values are filled with the most frequent value (mode).
Encoding Categorical Variables:
The Sex and Embarked columns are converted from categorical to numerical values using LabelEncoder.
Model Training
Feature and Target Separation: The dataset is split into features (X) and target (y), where X contains all columns except Survived, and y contains the Survived column.
Train-Test Split: The data is split into training and testing sets using an 80-20 split.
Random Forest Classifier: A Random Forest Classifier with 100 trees is trained on the training data.
Model Evaluation
Predictions: The trained model makes predictions on the test set.
Evaluation Metrics:
Accuracy: The model's accuracy is calculated as the proportion of correctly predicted instances.
Confusion Matrix: This matrix shows the counts of true positive, true negative, false positive, and false negative predictions.
Classification Report: This report provides precision, recall, and F1-score for each class.
Results
Accuracy: The model achieved an accuracy of 0.8268 (or 82.68%).
