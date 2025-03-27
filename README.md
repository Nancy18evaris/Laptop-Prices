This dataset, sourced from Kaggle, contains 11,768 records of laptops with various hardware specifications and prices. It is designed for predictive modeling, price estimation, and exploratory data analysis, reflecting real-world factors that influence laptop prices.

DATASET FEATURES
Brand: Manufacturer (e.g., Dell, HP, Apple, Asus, Lenovo)
Processor: CPU model (Intel i3/i5/i7/i9, AMD Ryzen 3/5/7/9)
RAM (GB): Memory size (4GB to 64GB)
Storage: Type and size (e.g., 256GB SSD, 1TB HDD)
GPU: Integrated or dedicated (e.g., Nvidia GTX 1650, RTX 3060)
Screen Size (inch): Display size (e.g., 13.3", 15.6")
Resolution: Screen resolution (e.g., 1920x1080, 3840x2160)
Battery Life (hours): Estimated battery life (4-12 hours)
Weight (kg): Laptop weight (1.2kg - 3.5kg)
Operating System: Windows, macOS, Linux, FreeDOS
Price ($): Target variable (laptop price in USD)

USE CASES
✔ Price Prediction: Build ML models to predict laptop prices.
✔ Market Analysis: Identify pricing trends based on configurations.
✔ Feature Importance: Analyze which specifications impact pricing the most.

SUPERVISED MACHINE LEARNING SCENARIOS
Scenario 1 (Classification):
If Brand is the target variable, other features become independent variables.
Since Brand has categories (Apple, HP, Asus, etc.), this is a classification problem.

Scenario 2 (Regression):
If Price is the target variable, other features are independent.
Since Price has continuous values, this is a regression problem.

POTENTIAL MODELS
Classification: Decision Trees, Random Forest, Logistic Regression, Neural Networks.
Regression: Linear Regression, Random Forest Regressor, XGBoost, Neural Networks.
