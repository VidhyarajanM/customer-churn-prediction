# 🚀 Telecom Customer Churn Prediction

## 📌 Project Overview
Predicting customer churn is critical for telecom companies to retain valuable customers. This project leverages **advanced machine learning and deep learning techniques** to identify at-risk customers, enabling proactive retention strategies. We implemented **Neural Networks, XGBoost, Random Forest, Gradient Boosting, and an Ensemble Stacking Model**, achieving **high accuracy and strong predictive power**.

## 📂 Dataset Details
- **Dataset Name**: `customer_churn`
- **Source**: Telecom customer records
- **Features**: Customer demographics, usage patterns, and service attributes
- **Target Variable**: `Churn` (1 = Churned, 0 = Retained)

## 🔍 Data Analysis & Preprocessing
- **Exploratory Data Analysis (EDA)** to uncover key insights
- **Feature Engineering** for enhanced model performance
- **Data Scaling** using `StandardScaler` for better numerical stability

## 🏆 Model Implementation & Performance
### 1️⃣ Deep Learning - Neural Network (Keras)
- Multi-layer Perceptron (MLP)
- **Accuracy**: 70.19%
- **ROC AUC Score**: 76.17%

### 2️⃣ Machine Learning Models
| Model | Accuracy | ROC AUC |
|--------|------------|------------|
| Random Forest | TBD | TBD |
| XGBoost | TBD | TBD |
| Gradient Boosting | TBD | TBD |
| **Stacking Model (Final)** | **80.30%** | **85.70%** |

✅ **Stacking Classifier** (Best Performing Model)
- **Base Models**: Random Forest, XGBoost, Gradient Boosting
- **Meta Model**: Logistic Regression
- **Final Accuracy**: **80.30%**
- **ROC AUC Score**: **85.70%**

## 💻 How to Use This Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/telecom-churn-prediction.git
   cd telecom-churn-prediction
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Train the Model**:
   ```python
   python train_model.py
   ```
4. **Make Predictions**:
   ```python
   python predict.py --input data/sample_input.csv
   ```

## 🔮 Future Enhancements
- Advanced hyperparameter tuning
- Additional feature engineering techniques
- Model deployment using Flask or FastAPI
- Explainability via SHAP & LIME visualizations

## 📂 Project Assets
- **Neural Network Model**: `telecom_churn_nn_model_optimized.keras`
- **Scaler**: `scaler_optimized.pkl`
- **Stacking Model**: `stacking_model.pkl`

## 👨‍💻 About the Author
**Vidhu** - Passionate Data Scientist & AI Enthusiast, transforming raw data into actionable insights.

🚀 *Let's connect! Feel free to reach out or contribute to this project.*
