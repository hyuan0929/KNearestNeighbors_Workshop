👥 Team Members

Ce Chen (9007166)

Haibo Yuan (9010929)

Zhuoran Zhang (9048508)

📌 Project Summary

This project implements a K-Nearest Neighbors (KNN) classifier using the Pipeline Pattern, following the workshop requirement to:

Chain data loading, preprocessing, training, and evaluation in a clear pipeline.

The dataset used is Breast Cancer Wisconsin (Diagnostic) from the UCI Machine Learning Repository.

Data is acquired from a Neon PostgreSQL database, with a fallback to a local CSV file for reproducibility.

🔄 Pipeline Structure

The implementation includes four modular steps:

load_data() – Load data from Neon (fallback to CSV)

preprocess_data() – Clean, split, and scale data

train_model() – Train KNN classifier

evaluate_model() – Evaluate performance (accuracy, classification report, confusion matrix)

All steps are executed in a structured main pipeline block.

📊 Model Performance

Accuracy: ~94.7%

Strong precision and recall for both classes

🛠 Tools Used

Python, pandas, scikit-learn, SQLAlchemy, Neon PostgreSQL