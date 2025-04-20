
# 🩺 Disease Prediction Symptoms Based System

A system designed to predict potential diseases based on the symptoms provided by the user.

## 📜 Description

This project leverages multiple machine learning algorithms, including K-Nearest Neighbors (KNN), Random Forest, Naive Bayes, and Support Vector Machine (SVM), to predict diseases based on symptoms inputted by users. The goal is to assist in early diagnosis and support healthcare professionals.

## 💻 Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/LincyBainiwal/Disease_prediction_symptoms_based_system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Disease_prediction_symptoms_based_system
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Disease.ipynb
   ```

2. Follow the instructions in the notebook to input symptoms and obtain predictions.

## 📊 Data

This project uses the following datasets:
- **training.csv**: Contains the training data for model training.
- **testing.csv**: Contains the testing data for model evaluation.
- **database.db**: The SQLite database used to store detailed information.

## ⚙️ Algorithms Used

This project implements the following machine learning algorithms:
- K-Nearest Neighbors (KNN)
- Random Forest
- Naive Bayes
- Support Vector Machine (SVM)

### 🧠 How the Algorithms Work

1. **K-Nearest Neighbors (KNN)**
   - KNN is an instance-based learning algorithm that classifies new instances based on the majority label of the K-nearest data points in the feature space.
   - In this project, when a user inputs symptoms, KNN calculates the distance between the user’s symptoms and all training samples. It selects the K closest samples and predicts the disease based on the most common outcome among these neighbors.

2. **Random Forest**
   - Random Forest is an ensemble method that constructs multiple decision trees and merges them together to improve prediction accuracy and stability.
   - In this project, it creates a group of decision trees using different subsets of training data and features, aggregating the predictions of individual trees to arrive at a robust final classification.

3. **Naive Bayes**
   - This probabilistic classification technique is based on Bayes' theorem and assumes independence among predictors.
   - For disease prediction, Naive Bayes evaluates how likely each disease is given the input symptoms, processing the frequency of symptoms associated with each disease from the training data to compute probabilities.

4. **Support Vector Machine (SVM)**
   - SVM finds the hyperplane that best separates different classes in the feature space and aims to maximize the margin between the closest points (support vectors) of each class.
   - In this project, SVM creates a decision boundary between different diseases based on symptoms, allowing it to classify the symptoms into discrete disease categories effectively.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the project's coding standards.

---

Thank you for checking out this project! 😊
```

