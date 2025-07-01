# DATA-PIPELINE-DEVELOPMENT
# 🔄 Data Pipeline Development – Task 1 (CODTECH Internship)

Automated **ETL pipeline** built using **Pandas** and **Scikit‑learn** during the CODTECH Data Science internship. This project demonstrates how to systematically **Extract, Preprocess, Transform**, and **Load** real-world data.

---

## 📌 Project Overview

This ETL pipeline:
1. **Extracts** raw data from a CSV (e.g., chocolate sales).
2. **Preprocesses**:
   - Handles missing values (mode for categoricals, median for numerics).
   - Removes duplicates and parses dates.
   - Converts booleans to integers.
3. **Transforms**:
   - Label-encodes categorical features.
   - Scales numeric columns (e.g., `Qty`, `Amount`) using `StandardScaler`.
4. **Loads** the cleaned and transformed data to a new CSV file.

Inspired by real-world pipelines using Pandas and Scikit-learn :contentReference[oaicite:1]{index=1}.

---

## 🗂️ Repository Structure
data-pipeline-task1/
├── data/
│ ├── raw_data.csv
│ └── processed_data.csv
├── etl_pipeline.ipynb # Notebook with full ETL workflow
├── etl_pipeline.py # Script version (optional)
├── requirements.txt
└── README.md

---

## ⚙️ Technologies Used

- Python 3.x  
- pandas  
- scikit-learn (LabelEncoder, StandardScaler)  
- joblib *(optional)* for saving pipelines

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/data-pipeline-task1.git
   cd data-pipeline-task1

2. **Install dependencies**:
   pip install -r requirements.txt
   
3. **Run the pipeline**:
   In Jupyter: open and run etl_pipeline.ipynb
   

👀 **Why It Matters**

1. Creates clean, consistent data for ML/analytics.
2. Reproducible pipeline—run on new datasets with ease, avoids manual errors.
3. Establishes a scalable structure ready for deployment or integration.


Crafted by Nisha during the CODTECH internship
Mentor: Neela Santosh 
