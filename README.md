# Heart Disease Data Analysis Project

## 📌 Project Overview
This project is a simple end-to-end data analysis pipeline built on the Heart Disease dataset from Kaggle.  
The goal of the project is to demonstrate key steps of a data science workflow:
- Exploratory Data Analysis (EDA)
- Data cleaning
- Feature engineering
- Clear documentation and reproducible code

This project was created as part of a university assignment.

---

## 📂 Dataset
- **Source:** Kaggle – Heart Disease Dataset  
- **Link:** https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
- **Target variable:** `target` (presence of heart disease)

---

## 🛠️ Project Structure
ds_project/
│
├── data/
│ └── heart.csv
│
├── src/
│ ├── data_analysis.ipynb
│ ├── data_preparation.py
│ ├── feature_engineering.py
│ ├── eda.py
│ └── main.py
│
├── requirements.txt
└── README.md


---

## 🔍 Exploratory Data Analysis (EDA)
During EDA, the following steps were performed:
- Inspection of dataset shape and column types
- Summary statistics for numerical features
- Target variable distribution
- Correlation analysis between features
- Identification of potential relationships between variables and heart disease

---

## 🧹 Data Cleaning
- Checked for missing values
- Imputed missing numeric values using **median strategy**
- Ensured dataset consistency before further processing

---

## ⚙️ Feature Engineering
New features were created to enrich the dataset:
- **Age groups** created from the `age` feature
- **Interaction feature** combining cholesterol and maximum heart rate

These features aim to capture non-linear patterns and relationships that may help a predictive model.

---

## 🚀 How to Run the Project

1. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows

2. Install dependencies

pip install -r requirements.txt

3. Run the analysis

python src/data_analysis.py

## Requirements

All required packages are listed in requirements.txt.
