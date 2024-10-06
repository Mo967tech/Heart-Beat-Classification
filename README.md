# Heart-Beat-Classification
## This project demonstrates the application of various supervised machine learning algorithms to classify heartbeat data, using a dataset from Kaggle. The goal is to predict the type of heartbeat based on electrocardiogram (ECG) signals using models such as Decision Tree, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Logistic Regression. Below is a brief description of the steps involved:

### 1. Data Preparation
#### The project begins by downloading the heartbeat dataset, which contains ECG readings from different patients.
#### After loading the dataset, features are renamed, and the ECG data is visualized to understand patterns in heart rate variation.
### 2. Data Preprocessing
#### StandardScaler is used to normalize the dataset, ensuring that all features have the same scale.
#### The target variable is highly imbalanced, so SMOTE (Synthetic Minority Over-sampling Technique) is employed to balance the classes and improve model performance.
#### PCA (Principal Component Analysis) is applied to reduce the dimensionality while preserving 95% of the variance in the data.
### 3. Model Training and Evaluation
#### Decision Tree, Random Forest, SVM, KNN, and Logistic Regression classifiers are trained on the processed dataset.
#### Performance of each model is evaluated using metrics like accuracy, precision, recall, f1-score, and confusion matrix.
### 4. Results
#### Random Forest achieved the best performance with 96.46% accuracy, followed by KNN with 93.6% accuracy.
#### Logistic Regression performed poorly (52%) due to the complexity of the data and lack of linear separability.
#### The results suggest that ensemble methods and non-linear classifiers like Random Forest are more effective in this task.
