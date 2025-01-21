Cancer Diagnosis using Logistic Regression

This project demonstrates the implementation of Logistic Regression for predicting breast cancer diagnosis (malignant or benign) using a publicly available dataset.

Dataset

The dataset is sourced from the YBIFoundation GitHub repository. It contains features extracted from digitized images of breast cancer tissue.

Dataset Details:

Target Variable: diagnosis (M = Malignant, B = Benign)

Features: Mean, standard error, and worst values of various cell nuclei measurements.

Columns Dropped: id, Unnamed: 32.



---

Project Steps

1. Data Import and Exploration

Load the dataset using pandas and explore it using info() and describe().


2. Feature Selection

Target variable: diagnosis.

Features: All columns except id, diagnosis, and Unnamed: 32.


3. Train-Test Split

Split the dataset into training (70%) and testing (30%) sets using train_test_split from sklearn.


4. Model Selection

Logistic Regression is used as the classification model.


5. Model Training

The model is trained using the training data (X_train, y_train).


6. Prediction

Predictions are generated on the test set (X_test).


7. Model Evaluation

Evaluate the model using metrics:

Confusion Matrix

Accuracy Score

Classification Report




---

Code Overview
Dependencies

pandas

scikit-learn


Key Functions and Methods

LogisticRegression from sklearn.linear_model

train_test_split from sklearn.model_selection

confusion_matrix, accuracy_score, and classification_report from sklearn.metrics.



---

Results

Model Performance:

Confusion Matrix:
Displays the true positives, true negatives, false positives, and false negatives.

Accuracy Score:
Indicates the percentage of correct predictions.

Classification Report:
Provides precision, recall, F1-score, and support for each class.



---

How to Run

1. Clone the repository:

git clone <repository-url>
cd <repository-folder>


2. Install dependencies:

pip install pandas scikit-learn


3. Run the script in your Python environment (e.g., Jupyter Notebook, VS Code, etc.).






#Conclusion

This project highlights how logistic regression can be applied to medical datasets for binary classification tasks. The model achieves good performance, demonstrating its potential for aiding cancer diagnosis.


Feel free to contribute or provide feedback!


