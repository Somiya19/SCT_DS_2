# 🚢 Titanic Survival Analysis

This project analyzes the famous Titanic dataset using Python.  
It explores the factors that influenced passenger survival, such as **gender, age, passenger class, and fare**.  

## 📂 Files in this Repository
- `titanic_analysis.ipynb` → Google Colab / Jupyter Notebook with full analysis & visualizations.  
- `train.csv` → Training dataset (from Kaggle Titanic dataset).  
- `test.csv` → Test dataset (optional).  
- `gender_submission.csv` → Example submission file (optional).  
- `README.md` → Project description (this file).

## 🛠️ Tools & Libraries Used
- **Python**  
- **Pandas** → data manipulation  
- **NumPy** → numerical operations  
- **Matplotlib & Seaborn** → visualizations  
- **SciPy & Statsmodels** → statistical tests  

## 📊 Analysis Performed
1. **Data Cleaning**
   - Filled missing `Age` with median  
   - Filled missing `Embarked` with mode  
   - Dropped `Cabin` column (too many missing values)  

2. **Exploratory Data Analysis (EDA)**
   - Gender vs. Survival (`countplot`)  
   - Passenger Class vs. Survival  
   - Age distribution  
   - Fare distribution vs. Survival  
   - Correlation heatmap of numerical features  

3. **Statistical Tests**
   - **Chi-square test** → Relation between Passenger Class & Survival  
   - **Z-test** → Gender difference in survival  

## 📌 Key Insights
- Females had a significantly higher survival rate than males.  
- First-class passengers were more likely to survive compared to third-class passengers.  
- Younger passengers had slightly better chances of survival.  

## 🚀 How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/titanic-analysis.git
