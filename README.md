# Breast Cancer Classification (Malignant vs. Benign)

This project was developed as part of my **Diploma in Artificial Intelligence and Machine Learning**. It features a machine learning pipeline designed to classify breast cancer tumors based on clinical measurements.

## 📌 Project Overview
The goal of this project is to provide a diagnostic tool that identifies whether a breast mass is **Malignant** (Dangerous) or **Benign** (Safe). Using the Breast Cancer Wisconsin (Diagnostic) dataset, the model analyzes cell nuclei characteristics to make highly accurate predictions.

## 📊 Dataset Details
- **Instances:** 569
- **Features:** 30 numeric predictive attributes (e.g., radius, texture, perimeter, area, smoothness, etc.)
- **Target Variable:** `diagnosis` (M = Malignant, B = Benign)
- **Data Source:** UCI Machine Learning Repository / Scikit-learn datasets.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** - `Pandas`: Data manipulation and analysis.
  - `NumPy`: Numerical computing and array reshaping.
  - `Scikit-learn`: Machine learning model implementation and evaluation.
  - `Matplotlib` & `Seaborn`: Data visualization and correlation heatmaps.

## ⚙️ Project Workflow
1. **Data Preprocessing:** Handled missing values (removed `Unnamed: 32`) and encoded the target labels.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and correlations to understand key tumor indicators.
3. **Model Building:** Implemented a classification model using `sklearn`.
4. **Reshaping Logic:** Integrated a prediction system that reshapes raw input data using `numpy.reshape(1, -1)` to handle single-patient diagnostics.
5. **Evaluation:** Validated the model performance on test data.

## 🚀 How to Use
To run the prediction system within the notebook:
1. Provide the clinical measurements as a tuple/list.
2. The system converts the input to a NumPy array.
3. The model outputs the result:
    - **Result 0:** The Breast Cancer is **Benign** (Safe).
    - **Result 1:** The Breast Cancer is **Malignant** (Dangerous).

## 📂 File Structure
- `Breast_Cancer__Project.ipynb`: The main Jupyter notebook containing the code.
- `data.csv`: The dataset used for training and testing.

---
*Developed as part of my academic journey in Artificial Intelligence and Machine Learning.*
