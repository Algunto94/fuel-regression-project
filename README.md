# 🚗 Fuel Consumption Regression

A simple linear regression project to predict distance traveled (in kilometers) based on fuel consumption (in liters).

## 🎯 Objective
This project demonstrates the application of supervised machine learning (linear regression) to estimate how far a vehicle can travel based on the amount of fuel used. It is a practical example for beginners transitioning into data science or analytics roles.

## 📊 Dataset
The dataset consists of two columns:
- `Liter`: the amount of fuel consumed
- `Kilometer`: the distance traveled by a vehicle

> 📌 **Disclaimer:**  
> The dataset used in this project is sourced from the book  
> _"Pengenalan Machine Learning dengan Python"_ by **Dios Kurniawan**, Chapter 4.  
> It is used here strictly for educational and non-commercial purposes.

## ⚙️ Tools and Libraries
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📈 Results
- **R² Score (training set):** 0.9798
- The model predicts mileage with a typical error range of ±10 km
- The relationship between fuel used and distance traveled shows a strong linear correlation

## 📂 Files
- `fuel_regression.ipynb`: Jupyter Notebook containing the code, modeling process, and visualizations
- `bensin.csv`: dataset used for modeling
- `regression_plot.png`: (optional) regression line visualization

## 📌 Sample Prediction Output

| Actual (KM) | Predicted (KM) |
|-------------|----------------|
| 102.0       | 107.5          |
| 167.0       | 172.1          |
| 278.0       | 269.0          |
| 65.0        | 75.2           |

## 🧠 Key Takeaways
- Linear regression is effective for numeric prediction with clear linear relationships
- Basic regression projects like this are useful for building foundational portfolio pieces
- The model can be extended by adding more features (e.g. engine RPM, vehicle type, route type)

## ✍️ Author
Agustina – Data Science Enthusiast  
GitHub: [https://github.com/Algunto94](https://github.com/Algunto94)
