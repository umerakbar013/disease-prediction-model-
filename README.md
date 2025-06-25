# disease-prediction-model-
internship project jupyter notebook

Task Objective Build a machine learning model that predicts the most likely disease a patient might have, based on a set of symptoms. This can be used in healthcare applications to assist doctors and medical personnel in preliminary diagnostics

Dataset Used Source: Local CSV file (dataset.csv)

Description: The dataset contains multiple symptom columns (Symptom_1, Symptom_2, ..., Symptom_n) and a target column Disease.

Preprocessing:

Missing values filled with 'none'

All symptoms encoded into binary columns (multi-hot encoding)

Target disease labels encoded using LabelEncoder Model Applied Algorithm: Random Forest Classifier

Why Random Forest: It handles multi-class classification well and works effectively with high-dimensional binary feature sets (like multi-hot symptom encodings).

Key Results and Findings Model Accuracy: Achieved an accuracy of ~X.XX% on the test set (replace with actual accuracy printed).

Evaluation Metrics:

Used classification_report to evaluate precision, recall, and F1-score for each disease class.

The model showed strong performance in correctly identifying common diseases.

Model Exported: The trained model and label encoder are saved using joblib:

disease_model.pkl

label_encoder.pkl

Files Included disease_prediction.ipynb or .py: The complete source code

dataset.csv: Input dataset

disease_model.pkl: Trained model file

label_encoder.pkl: Encoded disease label mappings

README.md: Project summary and instructions
