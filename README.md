### Pakistan Suicide Attacks: Exploratory Data Analysis & Data Cleaning
## 📊 Project Overview
This project focuses on the exploratory data analysis (EDA) and rigorous data cleaning of historical security incident records in Pakistan using Python (Pandas, NumPy, Matplotlib, and Seaborn). The primary goal is to transform a raw, messy dataset into a clean, structured format ready for statistical modeling, trend analysis, and geospatial visualization.

## 🛠️ Data Cleaning & Preprocessing Workflow
Real-world datasets often contain missing values, inconsistencies, and formatting errors. The following preprocessing steps were applied to ensure data integrity:

Handling Missing Values: Evaluated missingness across columns to determine appropriate imputation strategies.

Mode Imputation: Filled missing categorical values for day types using the statistical mode.

Random Categorical Imputation: Applied random categorical sampling to preserve variance for target types without introducing artificial skew.

Mean Imputation: Replaced missing numerical entries for casualties (such as maximum killed and injured metrics) using mean values where applicable.

Feature Standardization: Cleaned date-time columns, standardized text fields, and removed redundant whitespace or formatting errors.

## 📈 Exploratory Data Analysis (EDA) Insights
The analysis explores several core dimensions of the dataset:

Geospatial & Regional Breakdown: Examined attack frequencies across different provinces and major cities to identify high-density impact zones.

Temporal Trends: Analyzed attack distributions over years, months, and specific day types to uncover chronological patterns.

Casualty Impact Analysis: Evaluated the correlation between attack methods, targets, and resulting fatalities or injuries.

🗂️ Repository Structure
Plaintext
📦 pakistan-suicide-attacks-eda
├── 📂 data/
│   ├── PakistanSuicideAttacks Ver 11 (30-November-2017).csv
│   └── Cleaned_Data_of_Suicide_Attacks.csv
├── 📂 notebooks/
│   └── pakistan_suicide_attacks_eda.ipynb
└── README.md
## 🚀 Getting Started & Usage
To run the Jupyter Notebook locally:

Clone the repository:

Bash
git clone https://github.com/YOUR-USERNAME/pakistan-suicide-attacks-eda.git
Navigate to the project directory:

Bash
cd pakistan-suicide-attacks-eda
Install the required dependencies:

Bash
pip install pandas numpy matplotlib seaborn jupyter
Launch Jupyter Notebook:

Bash
jupyter notebook
