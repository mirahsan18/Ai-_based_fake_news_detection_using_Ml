📰 AI-Based Fake News Detection using Machine Learning

This project demonstrates how machine learning models can be applied to automatically detect fake news articles. Using a labeled dataset of real and fake news, we clean and preprocess the text, train multiple models, and compare their performance. The final product includes an interactive prediction interface where you can paste any news text to check if it’s likely real or fake.

🚀 Features

Data preprocessing & cleaning: removes HTML, punctuation, numbers, duplicates, and normalizes text.

Models trained:

Logistic Regression

Linear SVM (with calibration for probability outputs)

Multinomial Naive Bayes

Voting Classifier (ensemble of the above)

Evaluation metrics: accuracy, precision, recall, F1-score, ROC-AUC, confusion matrices.

Visualization: ROC/PR curves, confusion matrices, and bar plots comparing models.

Interactive UI: paste any news headline/article and get an instant prediction (Fake or Real).

Model saving: best pipeline is stored with joblib for reuse.

📊 Results (on held-out test set)

Linear SVC (Calibrated) performed best with:

Accuracy ≈ 99.4%

Precision ≈ 99.3%

Recall ≈ 99.6%

F1-score ≈ 99.5%

🛠️ Tech Stack

Python 3.11

Pandas, NumPy, Matplotlib

Scikit-learn

Joblib

ipywidgets (for interactive UI in Jupyter)

📂 How to Run

Clone this repo and install dependencies.

Place Fake.csv and True.csv datasets into your project folder.

Run the notebook / script to train models and launch the UI.

Use the text box in the UI to test any custom news input.

💡 Use Cases

Educational demo for text classification.

Prototype for fake news filtering systems.

Starting point for NLP + ML research.
