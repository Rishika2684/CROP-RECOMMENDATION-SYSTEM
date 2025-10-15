**🌾 Crop Recommendation System using Machine Learning**
**📌 Overview**

This project predicts the most suitable crop for a given piece of land based on soil and weather conditions. It enables farmers to make data-driven decisions, thereby improving yield and promoting sustainable agriculture.

**🧠 Objective**

To build a machine learning model that recommends the best crop to grow given soil nutrient levels and environmental factors.

**📊 Dataset**

Public dataset with 2200 samples and 8 features:
Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, Rainfall, and Crop Label.

Data is balanced with 100 samples per crop for 22 crops.

No missing or duplicate values.

**⚙️ Machine Learning Models Used**
**Algorithm**	                  **Accuracy**
Logistic Regression	         97.04%
Decision Tree	               99.54%
Random Forest	               99.77%

The Decision Tree Classifier was selected for deployment due to its simplicity, interpretability, and fast prediction time.

**🧩 Workflow**

Data Preprocessing (handling duplicates, splitting features/labels)

Model Training and Evaluation

Saving model using joblib

Testing model with new data

Ready for integration into web/mobile apps

**🚀 Tech Stack**

Python

Pandas, NumPy

Scikit-learn

Joblib
