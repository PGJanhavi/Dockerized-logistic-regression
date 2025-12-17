# Logistic Regression Classification using Docker
# 📌 Project Overview

This project demonstrates a machine learning classification pipeline using Logistic Regression, packaged and executed inside a Docker container.
A synthetic dataset is generated, the model is trained, evaluated, and used to make predictions on new data.

This project showcases ML fundamentals + Dockerization, making it suitable for deployment-ready ML workflows.

# 📊 Dataset Description

Synthetic dataset generated using make_classification

Total samples: 1000

Features: 10

Classes: 2 (Binary Classification)

Train/Test split: 80% / 20%

# 📈 Model Performance (Sample Output)
Accuracy: 0.83

Confusion Matrix:
[[75 14]
 [20 91]]

Classification Report:
precision    recall    f1-score
0   0.79      0.84      0.82
1   0.87      0.82      0.84


✔ Achieved 83% accuracy on test data

# 🐳 Docker Setup
Dockerfile Explanation

Uses Python 3.9 base image

Installs dependencies from requirements.txt

Copies project files

Runs ABC.py on container startup

▶️ How to Run the Project (Using Docker)
1️⃣ Build the Docker Image
docker build -t logistic-regression-app .

2️⃣ Run the Container
docker run logistic-regression-app


# 📌 Output will display:

Model accuracy

Confusion matrix

Classification report

Prediction for new input
