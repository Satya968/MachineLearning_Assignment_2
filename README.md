# Personality Cluster Classification & Founder Exit Prediction

This repository contains a complete machine-learning workflow for two tasks:
1. **Classifying individuals into personality clusters** using everyday behavioral indicators.
2. **Predicting a founder’s exit likelihood** using personal, professional, and startup performance features.

Both tasks share a unified pipeline including preprocessing, feature engineering, model training, evaluation, and final prediction generation.

---

##  Features

###  Data Preprocessing
- Missing-value imputation  
- Scaling of numeric features  
- One-hot / target encoding for categorical features  
- Label encoding of target classes  
- Train–validation split  

###  Exploratory Data Analysis
- Histograms of numeric features  
- Boxplots for outlier detection  
- Missing-value heatmaps  
- Correlation heatmaps  
- Target distribution plots  

###  ML Models Included
- Logistic Regression  
- Support Vector Machine (SVM)  
- XGBoost Classifier (with randomized hyperparameter tuning)  
- Keras MLP classifier (dense layers, batch norm, dropout, class weights)

###  Evaluation Metrics
- Accuracy  
- Macro-F1 Score  
- Cross-validation metrics  

###  Submission Pipeline
- Loads trained model + preprocessing artifacts  
- Processes test data  
- Generates CSV submission file  

---

| File / Folder | Description |
|---------------|-------------|
| **MPCP.ipynb** | ML pipeline with preprocessing, EDA, SVM, XGBoost |
| **Number2_1_keras.ipynb** | Keras MLP model training + inference |
| **train.csv** | Training dataset |
| **test.csv** | Test dataset |
| **submission.csv** | Generated predictions |
| **README.md** | Documentation |

---

##  Technologies Used
- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-Learn  
- XGBoost  
- TensorFlow / Keras  
- Category Encoders  
- Joblib  



