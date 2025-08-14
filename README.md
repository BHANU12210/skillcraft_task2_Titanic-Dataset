# skillcraft_task2_Titanic-Dataset

# Task 2 – Titanic Dataset: Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Description
This task involves cleaning the Titanic dataset and performing exploratory data analysis (EDA) to identify patterns, relationships, and trends affecting passenger survival.

## 📂 Dataset
- **File:** `titanic.csv`
- **Columns:**
  - Passenger details (Name, Age, Sex, Pclass, Ticket, Fare, Cabin, Embarked, etc.)
  - Survival status (0 = No, 1 = Yes)

## 🧹 Data Cleaning
- Filled missing `Age` with median age.
- Filled missing `Embarked` with mode.
- Filled missing `Fare` with median fare.
- Replaced missing `Cabin` values with "Unknown".
- Converted categorical columns to `category` data type.

## 📊 EDA Visualizations
- Survival Count
- Gender Distribution
- Survival by Gender
- Survival by Passenger Class
- Age Distribution (Histogram + KDE)
- Age vs Survival (Boxplot)
- Survival by Embarkation Port
- Survival by Siblings/Spouses Aboard
- Survival by Parents/Children Aboard
- Correlation Heatmap

## 📈 Key Insights
- Females had higher survival rates than males.
- Higher-class passengers (Pclass 1) had better survival chances.
- Age distribution showed most passengers were between 20–40 years old.
- Having family members aboard influenced survival.

## 📂 Output Files
- Cleaned dataset: `titanic_cleaned.csv`
- Visualizations: Saved inside the `screenshots` folder.

## ▶️ How to Run
1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
