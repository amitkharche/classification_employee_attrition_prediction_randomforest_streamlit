
![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Streamlit](https://img.shields.io/badge/built%20with-Streamlit-orange)


# 👨‍💼 Employee Attrition Prediction

## Business Use Case
Organizations lose valuable time and resources due to employee attrition. This project predicts which employees are likely to leave (Attrition = Yes), helping HR departments take proactive steps to retain top talent.

## Features Used
- Age
- Department
- Job Role
- Education Level
- Job Satisfaction
- Monthly Income
- Total Working Years
- Years at Company
- Overtime Status

## What's in `model_training.py`
- ✅ Data Cleaning
- ✅ Feature Selection
- ✅ Preprocessing Setup
- ✅ Train/Test Split
- ✅ Model Training (RandomForestClassifier)
- ✅ Model Evaluation (classification report)
- ✅ Model Saving
- ✅ Logging via print()

## How to Use
### 1. Clone the repository
   ```bash
   git clone https://github.com/amitkharche/classification_employee_attrition_prediction_randomforest_streamlit.git
   cd classification_employee_attrition_prediction_randomforest_streamlit

   ```

### 2. Train the Model
```
pip install -r requirements.txt
python model_training.py
```

### 3. Run Streamlit App
```
streamlit run app.py
```

### 4. Upload CSV File
- Upload employee data (same format as `employee_data.csv`)
- View and download attrition predictions

## 📁 Files Included
- employee_data.csv
- model_training.py
- app.py
- attrition_model.pkl
- attrition_features.pkl
- requirements.txt
- README.md

## 📬 Contact

If you have questions or want to collaborate, feel free to connect with me on
- [LinkedIn](https://www.linkedin.com/in/amitkharche)  
- [Medium](https://medium.com/@amitkharche)  
- [GitHub](https://github.com/amitkharche)

