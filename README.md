# Pima Diabetes AI Project

## Project Overview
This project predicts the likelihood of diabetes using the **Pima Indian Diabetes dataset**, enriched with **synthetic lifestyle features** such as sleep, stress, physical activity, diet, and water intake. The model is built using **Python** and **machine learning** (Random Forest Classifier) to provide a simple yet effective prediction system.

## Dataset
The dataset includes:

### Clinical Features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (target variable: 0 = no diabetes, 1 = diabetes)

### Lifestyle Features (Added for originality):
- sleep_hours: Average hours of sleep per night
- stress_level: Stress level (1–10 scale)
- physical_activity_mins: Daily exercise in minutes
- food_processed: 0 = No, 1 = Yes (consumption of processed foods)
- water_liters: Average daily water intake in liters
- family_history: 0 = No, 1 = Yes (family history of diabetes)

> These additional columns make the dataset **unique and portfolio-ready**.

## Model
- **Algorithm:** Random Forest Classifier  
- **Purpose:** Predict diabetes outcome (0 or 1)  
- **Evaluation:** Accuracy, confusion matrix, and classification report  

---

## How to Run
1. Download the dataset: `pima_diabetes_lifestyle.csv` from this repository  
2. Open the provided notebook (`.ipynb`) in **Google Colab**  
3. Run all cells to:
   - Load the dataset
   - Explore data
   - Train and evaluate the model
4. Optionally, download the trained model (`diabetes_model.pkl`) for further use  

---

## Portfolio / Learning Goals
This project demonstrates:
- Data preprocessing and feature addition  
- Beginner-friendly AI model building using Python  
- Use of synthetic lifestyle data to make datasets original  
- Uploading projects to GitHub to showcase skills to recruiters  

---

## Optional Next Steps
- Improve model performance with hyperparameter tuning  
- Visualize feature importance using `matplotlib` or `seaborn`  
- Explore other ML algorithms like Logistic Regression or XGBoost  
- Participate in Kaggle competitions to apply skills on real-world medical datasets



