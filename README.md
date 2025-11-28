# AQI-Prediction-Using-LightGBM
A machine learning project that predicts Air Quality Index (AQI) levels using pollutant data. It includes data preprocessing, feature engineering, model training, evaluation, SHAP explainability, and saving the best model for future deployment.

### 📌 Project Highlights
- Predicts AQI categories (Low, Moderate, High, Very High)
- Handles missing values and performs feature engineering
- Compares multiple machine learning models
- Uses SHAP for model explainability
- Exports the best model using `joblib` for deployment

---

### 📂 Dataset  
The dataset is **not included** in this repository.  
You may download any AQI dataset (e.g., from Kaggle or other public sources) and update the file path inside the notebook accordingly.

---

### ⚙️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook ML_IA1_final.ipynb
