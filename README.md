# Exploratory Data Analysis (EDA) - Titanic Dataset

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic Dataset** to understand trends and factors influencing passenger survival. The dataset contains information about passengers, including their **age**, **gender**, **class**, **fare**, and whether they **survived** or not.

---

## Objective
- Visualize key features of the Titanic dataset (age, gender, class, survival).
- Identify trends and relationships between features.
- Gain insights into the factors that contributed to survival rates.

---

## Tools Used
- **Python**: The programming language used.
- **Pandas**: For handling and analyzing the data.
- **Matplotlib & Seaborn**: For creating visualizations.

---

## Dataset Description
The Titanic dataset includes these main columns:
- **PassengerId**: Unique ID of the passenger.
- **Pclass**: Passenger class (1st, 2nd, 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Fare**: Fare paid by the passenger.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).
- **Survived**: Whether the passenger survived (1) or not (0).

---

## Steps in the Analysis
1. **Load Data**: The dataset was loaded into a Pandas DataFrame.
2. **Clean Data**: Missing values were handled, and irrelevant columns were removed.
3. **EDA**: Exploratory Data Analysis was done to:
   - Visualize the distribution of **Age**.
   - Compare **Survival Rates** by **Gender** and **Class**.
   - Create a **Correlation Heatmap**.
   - Explore relationships using a **Pairplot**.

---

## Visualizations
1. **Histogram**: Shows the **Age Distribution** of passengers.
2. **Boxplot**: Compares **Age** across different **Passenger Classes**.
3. **Countplot**: Shows the **Survival Rate by Gender** and **Passenger Class**.
4. **Heatmap**: Displays the **correlation between features**.
5. **Pairplot**: Visualizes relationships between **Survival**, **Age**, **Fare**, and **Pclass**.

---

## Key Insights
- **Age Distribution**: Most passengers are young, with a few older passengers.
- **Survival Rate by Gender**: **Females** had a higher survival rate than **males**.
- **Survival Rate by Class**: **1st class** passengers had the highest survival rate, while **3rd class** had the lowest.
- **Fare vs. Survival**: Higher **fare** is associated with a higher chance of survival.
- **Correlations**: **Pclass** negatively correlates with **Fare** and **Survival**.

---

## Summary
- **Higher-class passengers** had a higher chance of survival.
- **Females** were more likely to survive than **males**.
- **Age** had less impact on survival, but **Pclass** and **Fare** were more significant factors.

---

## File Structure
