# Elevate-Labs-Task-5
# 🚢 Exploratory Data Analysis on the Titanic Dataset

This project performs **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** to uncover patterns and insights about the factors influencing passenger survival.

## 📁 Project Structure

- `eda.ipynb` – Jupyter Notebook with full EDA code and visualizations.
- `titanic.csv` – The dataset used for analysis (sourced from Kaggle).
- `eda.pdf` – A compiled PDF export of the notebook for easy viewing.
- `Exploratory Data Analysis on the Titanic Dataset.docx` – A report summarizing the analysis and insights.

## 🧠 Objectives

- Clean and preprocess the dataset.
- Visualize data distributions and relationships.
- Analyze survival rates across different groups.
- Identify the influence of features like class, age, gender, and fare on survival.

## 🛠️ Technologies Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)

## 📊 Key Insights

- **Survival Rate:** Less than 50% of the passengers survived.
- **Gender:** Females had a much higher survival rate compared to males.
- **Pclass & Fare:** Passengers in higher classes (1st class) with higher fares had better survival chances.
- **Age:** Children had slightly better survival odds, but age wasn’t a strong overall predictor.
- **Correlation:** Strong negative correlation between `Pclass` and `Survived`, positive correlation between `Fare` and `Survived`.

## 🧹 Data Preprocessing

- Filled missing `Age` values with the median.
- Filled missing `Embarked` values with the mode.
- Dropped the `Cabin` column due to too many missing values.
- Converted data types and standardized formats where necessary.

## 📈 Visualizations

- Countplot of survival
- Boxplots and scatterplots for age vs survival
- Pairplot showing multivariate relationships
- Heatmap for correlation analysis


