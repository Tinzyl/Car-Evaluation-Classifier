# Car-Evaluation-Classifier
A lightweight Flask-based web application for predicting the quality of cars using multiple machine learning algorithms. Users can input car attributes, select an algorithm, and view results with detailed metrics and predictions.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue) ![Flask](https://img.shields.io/badge/Flask-2.0-green) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0-orange)

---

## ✨ Features

- **Interactive Web Interface**: Simple interface to input car details and view predictions.
- **Multiple Algorithms**: Choose from Logistic Regression, Decision Tree, Random Forest, and SVC.
- **Performance Metrics**: Accuracy, Precision, Recall, and F1-score provided for each prediction.
- **Extensible Design**: Easily add more algorithms or features.

---

## 📊 Results

| Algorithm          | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression | 87.5%   | 0.89      | 0.85   | 0.86     |
| Decision Tree       | 91.0%   | 0.93      | 0.90   | 0.91     |
| Random Forest       | 94.2%   | 0.94      | 0.94   | 0.94     |
| SVC                 | 89.7%   | 0.90      | 0.89   | 0.89     |

---

## 🚀 Quick Start

1. Clone the repository:
   git clone https://github.com/Tinzyl/car-evaluation-classifier.git
   cd car-evaluation-classifier
2. Install dependencies:
   pip install -r requirements.txt
3. Run the application:
   python main.py
4. Access the app: Open your browser and go to http://localhost:5000

---

## ✨ How It Works

- **Data Preprocessing**: Reads and label-encodes the car dataset.
- **Model Selection**: Choose from pre-defined algorithms (Logistic Regression, Decision Tree, etc.).
- **Prediction**: User inputs are processed to predict the car class (e.g., Accurate, Good).
- **Visualization**: Performance metrics and predictions are displayed in the web interface.


