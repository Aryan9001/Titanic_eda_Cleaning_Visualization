# Titanic Survival Exploratory Data Analysis

## Project Overview
This project analyzes the Titanic dataset to explore patterns in passenger survival. Using data visualization and exploratory data analysis (EDA), we identify how factors like gender, class, age, and family size influenced survival outcomes.

## Dataset
- Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)
- File used: `train.csv`

## Steps Performed
- Data loading and inspection
- Handling missing values (`Age`, `Embarked`)
- Dropping irrelevant columns (`Cabin`, `Ticket`)
- Encoding categorical variables (`Sex`, `Embarked`)
- Feature engineering (`FamilySize`, `IsAlone`)
- Data visualization using Seaborn and Matplotlib

## Key Insights

1. **Gender and Survival**
   - Female passengers had a significantly higher survival rate than males.
   - Social norms like "women and children first" likely influenced rescue decisions.

2. **Passenger Class and Survival**
   - First-class passengers had the highest survival rate.
   - Third-class passengers had the lowest survival, indicating class-based differences in safety.

3. **Age and Survival**
   - Children (age < 10) had higher survival rates.
   - Passengers aged 20–35 were the largest group but had lower chances of survival.

4. **Family Size and Survival**
   - Solo travelers had the lowest survival rate.
   - Small families (2–3 members) had better outcomes; survival dropped in large families (≥5).

## Visualizations
*Included in the notebook. Can also be viewed in the `/images` folder.*

## Tools Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Google Colab

## Future Work
- Apply machine learning models to predict survival
- Include additional feature engineering
