# Titanic Survivorship & Demographic Insights

An in-depth exploratory data analysis (EDA) and data cleaning project on the historic Titanic passenger manifest, examining demographic and socio-economic influences on survival probability.

## 📌 Project Overview
The Titanic disaster is one of the most infamous maritime events in history. This project applies data cleaning techniques and exploratory data analysis to the passenger manifest to uncover patterns, validate historical accounts (such as the "women and children first" policy), and analyze how socio-economic standing impacted survival rates.

## 🚀 Key Features
* **Data Cleaning Pipeline:** Handles missing data structural anomalies (e.g., imputing age distributions, adjusting embarked ports) and filters features for statistical relevance.
* **Demographic Analysis:** Segregates survivorship statistics by gender, passenger class (socio-economic status), age groups, and family presence.
* **Correlation Mapping:** Computes and visualizes linear/non-linear correlations between numeric passenger features and survival outcomes.
* **Intuitive Visualizations:** Includes customized distribution plots, count plots, correlation heatmaps, and survivorship breakdown pie charts.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing & Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

## 📈 Methodology & Pipeline
1. **Data Acquisition:** Sourced passenger demographics and survival indicators from the [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic).
2. **Data Cleaning & Preprocessing:**
   * Analyzed missing value patterns across `Age`, `Cabin`, and `Embarked`.
   * Imputed missing `Age` values utilizing median values partitioned by passenger class (`Pclass`).
   * Dropped columns with excessive missing data (e.g., `Cabin`) to maintain data integrity.
   * Handled categorical values for survival plotting compatibility.
3. **Exploratory Data Analysis (EDA):**
   * Dissected survival rates across multi-dimensional bins: Gender, Class, Age, and Fare.
   * Visualized variables using count plots and bivariate factor plots.
4. **Correlation Analysis:** Generated a Pearson correlation heatmap to establish strengths of associations between features (e.g., negative correlation between class number and survival).

## 💡 Key Insights
* **Gender Disparity:** Female passengers exhibited a significantly higher survival rate (~74%) compared to male passengers (~19%), strongly reflecting historical emergency protocols.
* **Socio-Economic Stratification:** First-class passengers had a much higher likelihood of survival compared to third-class passengers, pointing to class-based evacuation prioritization.
* **Fare & Cabin Class Correlation:** Higher ticket fares strongly correlated with increased survival rates, validating the socio-economic impact on passenger outcomes.

## 📂 Project Structure
```text
├── Task_02.ipynb                       # Exploratory Data Analysis & Cleaning Notebook
├── titanic.csv                         # Titanic passenger manifest dataset
└── README.md                           # Project documentation
```

## 👤 Author
* **Khan Sohail**
  * [LinkedIn](https://www.linkedin.com/in/khan-sohail-386b2027a)
  * Email: ks646397@gmail.com
