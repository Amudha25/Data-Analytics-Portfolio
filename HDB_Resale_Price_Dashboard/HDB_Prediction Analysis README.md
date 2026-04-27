📈 HDB Resale Price Prediction Model
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

📌 ## Project Overview
- This project builds a machine learning regression model to predict HDB resale flat prices in Singapore. Using historical transaction data, the model identifies key price drivers and produces price estimates that can help buyers benchmark fair value and sellers set competitive asking prices.
---
❓ Business Questions Answered
- What are the most significant factors that influence HDB resale prices?
- Can we accurately predict the resale price of a flat given its attributes?
- How much does floor level, flat type, and location affect price?
- Which features contribute most to price variation?
---
🔍 Key Findings
- Location (town) is the strongest single predictor of resale price, accounting for the largest share of price variance
- Floor area (sqm) has a strong positive linear relationship with resale price
- Storey range (higher floors) adds a measurable premium, especially in popular towns
- Remaining lease has a significant impact for flats with fewer than 70 years remaining
- The final model achieved an R² score of ~0.87 on the test set, meaning it explains ~87% of price variation
---
🛠️ Tools & Technologies
Tool	Purpose
- Python 3	Core programming language
- Pandas & NumPy	Data loading, cleaning, feature engineering
- Matplotlib & Seaborn	Exploratory data analysis (EDA) visualisations
- Scikit-learn	Model building, training, and evaluation
- SQL	Data extraction and filtering from database
- Jupyter Notebook	Interactive development and documentation
---
🔄 Project Workflow
```
1. Data Collection    →  SQL queries to extract resale transaction data
2. Data Cleaning      →  Handle nulls, outliers, data type fixes
3. EDA                →  Distribution plots, correlation matrix, boxplots
4. Feature Engineering→  Encode categorical variables (town, flat type, storey)
5. Model Building     →  Train Linear Regression & Random Forest models
6. Model Evaluation   →  RMSE, MAE, R² score comparison
7. Insights           →  Feature importance plot, interpretation
```
---
📊 Model Performance
- Model	R² Score	RMSE (SGD)
- Linear Regression	0.81	~$42,000
- Random Forest	0.87	~$31,000
- Random Forest was selected as the final model due to better handling of non-linear relationships.
---
📁 Repository Structure
```
Market Analysis/
├── data/
│   └── hdb_resale_data.csv          # Source dataset
├── notebooks/
│   └── HDB_Price_Prediction.ipynb   # Full Jupyter notebook (EDA + model)
├── sql/
│   └── data_extraction.sql          # SQL queries used for data pull
├── outputs/
│   ├── feature_importance.png       # Feature importance chart
│   └── model_predictions.csv        # Predicted vs actual price comparison
└── README.md
```
---
▶️ How to Run This Project
Clone the repository
```bash
   git clone https://github.com/Amudha25/Data-Analytics-Portfolio.git
   cd "Data-Analytics-Portfolio/Market Analysis"
   ```
Install dependencies
```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
Launch Jupyter Notebook
```bash
   jupyter notebook notebooks/HDB_Price_Prediction.ipynb
   ```
- Run all cells — The notebook runs end-to-end from data loading to model evaluation
---

