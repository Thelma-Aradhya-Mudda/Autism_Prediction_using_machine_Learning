# 🧠 Autism Prediction using Machine Learning

This project uses machine learning to predict whether a person is likely to have Autism Spectrum Disorder (ASD) based on their responses to a screening questionnaire and demographic data.

The goal is to assist early screening by building a reliable model that can classify individuals as ASD-positive or not, using real-world questionnaire data.

---

## 🚀 What This Project Does

- Loads and preprocesses the dataset (label encoding, handling imbalance with SMOTE)
- Trains classification models (Decision Tree, Random Forest, XGBoost)
- Evaluates models using accuracy, precision, recall, and F1-score
- Saves the best-performing model for later use with `pickle`

---

## 📂 Dataset Features

The dataset includes:
- Answers to 10 screening questions (A1_Score to A10_Score)
- Age, gender, ethnicity, jaundice history, and app usage
- Family history of autism, screening result, and relation to the respondent
- Target: `Class/ASD` indicating if the person likely has ASD (YES/NO)

---

## 💻 How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/autism-prediction-ml.git
   cd autism-prediction-ml
2. **Install Required Libraries**
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
3. **Open and Run the Notebook**
   Open Autism_Prediction_using_machine_Learning.ipynb in Jupyter Notebook or Google Colab and run all cells.
4. **Using the Trained Model**
   After training, the best model is saved using pickle. 
   


   

   
