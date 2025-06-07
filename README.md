# 🚗 Vehicle Type Classification using K-Nearest Neighbors (KNN)

This project demonstrates how to classify different types of vehicles (Car, Truck, Motorcycle, Bus) using the K-Nearest Neighbors algorithm based on key features like engine size, weight, number of wheels, and fuel efficiency.

---

## 🎯 Objective

To build a machine learning model capable of accurately classifying vehicle types, which can be useful for smart traffic systems, toll collection, and urban planning.

---

## 📊 Dataset Overview

| Feature         | Description                          |
|-----------------|------------------------------------|
| `EngineSize`    | Engine displacement in liters      |
| `Weight`        | Vehicle weight in kilograms        |
| `NumWheels`     | Number of wheels                   |
| `FuelEfficiency`| Fuel consumption (km per liter)    |
| `VehicleType`   | Target variable (Car, Truck, etc.) |

---

## 🧰 Tools & Libraries

- Python 🐍  
- `pandas` for data handling  
- `scikit-learn` for modeling and evaluation  
- `matplotlib` and `seaborn` for visualization

---

## ⚙️ How to Run

1. Clone or download the project files.  
2. Install required libraries if you haven’t already:
pip install pandas scikit-learn matplotlib seaborn
Run the Python script:
vehicle_type_knn.py
🔧 Key Features of the Code
Data loading and preprocessing (feature scaling, label encoding).

Stratified train-test split to maintain class distribution.

KNN model training with k=3.

Model evaluation including accuracy, classification report, and confusion matrix.

Fix applied for classification_report to handle missing classes in test data by specifying all class labels.

📈 Model Evaluation
Prints overall accuracy on the test set.

Displays detailed classification metrics (precision, recall, F1-score) for all vehicle types.

Shows a heatmap confusion matrix for visual inspection.

🚀 Real-World Applications
Automated traffic and vehicle monitoring

Toll booth classification systems

Urban traffic planning and control

Vehicle type detection in surveillance

📄 License
This project is open source under the MIT License.
