Heart Disease Prediction using Logistic Regression
📌 Overview
This project is a machine learning-based approach to predict the presence of heart disease in patients using the UCI Heart Disease dataset. It utilizes logistic regression to classify patients based on various medical attributes like age, cholesterol level, chest pain type, etc.

🔍 Problem Statement
To develop a binary classification model that predicts whether a person is likely to have heart disease based on their medical history and diagnostic measurements.

🎯 Objectives
Preprocess the dataset and handle missing values

Encode categorical variables and scale features

Train a logistic regression model

Evaluate using metrics like accuracy, precision, recall, F1-score

Visualize results using confusion matrix and other plots

📁 Dataset
Source: UCI Heart Disease Dataset

Format: CSV

Rows: ~920 entries

Columns: 16 features including target label num (converted to binary 0/1)

⚙️ Technologies Used
Python

Pandas

NumPy

Scikit-learn

Matplotlib & Seaborn (for visualization)

Jupyter Notebook

🧠 Model Used
Logistic Regression: A simple and effective algorithm for binary classification.

📊 Evaluation Metrics
Accuracy

Precision

Recall

F1 Score

Confusion Matrix

📂 Project Structure
Copy
Edit
Heart-Disease-Prediction/
├── dataset/
│   └── heart_disease_uci.csv
├── notebook/
│   └── 10_Heart_Disease_Prediction_Model_Project.ipynb
├── README.md
└── requirements.txt
👨‍💻 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
📌 Results Snapshot
Model Accuracy: ~86% (can vary)

Balanced Precision and Recall

Visualized Confusion Matrix

👥 Team Contribution
Kartik Kumar: Report preparation

Harshit & Kanishak Tyagi: Code development

Jayant Singh & Manasvi: PPT and visualization slides

📄 License
This project is open-source and free to use for educational purposes.
