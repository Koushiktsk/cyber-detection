##Cyberbullying Detection using Machine Learning (Linear SVC) & Flask

📌 Overview

This project is a Cyberbullying Detection System that classifies text messages as cyberbullying or not using a Linear Support Vector Classifier (LinearSVC). The backend is built with Flask, and the model achieves 97% accuracy in classification.

🚀 Features

Text Classification: Detects cyberbullying messages.

Machine Learning Model: Trained using a Linear Support Vector Classifier (SVC).

Flask Backend: Serves the model as a web application.

TfidfVectorizer: Used for text feature extraction.

📁 Project Structure

🛠️ Installation & Setup

1️⃣ Prerequisites

Ensure you have Python 3.x installed along with the following dependencies:

2️⃣ Run the Flask App

3️⃣ Access the Web App

Visit http://127.0.0.1:5000/ in your browser.

🔍 Model Training & Preprocessing

Dataset: A dataset containing labeled cyberbullying and non-cyberbullying messages.

Preprocessing Steps:

Tokenization & Lowercasing

Stopword Removal (Using stopwords.txt)

Feature Extraction with TfidfVectorizer

Training Algorithm: LinearSVC from sklearn.svm

🎯 Example Usage

Enter a message in the text box.

Click "Detect" to get real-time classification.

📊 Performance

Accuracy: 97%

Precision & Recall: Optimized for high recall to minimize false negatives.

🤖 Technologies Used

Machine Learning: sklearn.svm.LinearSVC

Text Processing: TfidfVectorizer

Backend: Flask

Serialization: pickle
