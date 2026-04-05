# 🚢 Titanic EDA Project

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns and factors affecting passenger survival. The analysis focuses on understanding relationships between demographic, socioeconomic, and survival variables.

---

## 🎯 Objectives

* Understand dataset structure and features
* Handle missing values and clean data
* Analyze survival trends based on different features
* Detect outliers and data distributions
* Visualize insights using Seaborn and Matplotlib
* Derive meaningful conclusions from the data

---

## 🛠️ Tech Stack

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Structure

```
TITANIC_EDA_PROJECT/
│
├── data/
│   └── titanic_train.csv
│
├── images/
│   ├── Age Distribution.png
│   ├── Age vs Fare.png
│   ├── Children vs Adult.png
│   ├── Correlation Heatmap.png
│   ├── Correlation with Survival.png
│   ├── FacetGrid with age.png
│   ├── Fare Distribution.png
│   ├── Fare vs Survival.png
│   ├── Null Value Check.png
│   ├── PairPlot.png
│   ├── Passengers by Gender.png
│   ├── Passengers by Survival.png
│   ├── Pclass vs Age.png
│   ├── Survival vs Gender.png
│   └── Survival vs Passengers.png
│
├── notebook/
│   └── Titanic_EDA_Project.ipynb
│
└── README.md
```

---

## 📊 Key Analysis Performed

* Data cleaning and preprocessing
* Missing value handling
* Univariate analysis (Age, Fare, Gender)
* Bivariate analysis (Survival vs Gender, Class, Fare)
* Outlier detection using boxplots
* Correlation analysis using heatmaps
* Feature engineering (e.g., Child classification)

---

## 🔍 Key Insights

* Female passengers had significantly higher survival rates than males
* First-class passengers were more likely to survive compared to third-class passengers
* Higher ticket fares were associated with better survival chances
* Children were prioritized during evacuation
* Socioeconomic status played a major role in survival outcomes



## 🚀 How to Run the Project

1. Clone the repository:

```
git clone https://github.com/your-username/Titanic_EDA_Project.git
```

2. Navigate to the project folder:

```
cd Titanic_EDA_Project
```

3. Install required libraries:

```
pip install numpy pandas matplotlib seaborn
```

4. Open the notebook:

```
jupyter notebook
```

---

## 🧠 Conclusion

The analysis shows that survival on the Titanic was strongly influenced by gender, age, and socioeconomic status. Female passengers, children, and first-class passengers had the highest probability of survival, highlighting the impact of social structure during the disaster.

---

## ✨ Future Improvements

* Apply Machine Learning models (Logistic Regression, Decision Trees)
* Improve feature engineering
* Deploy as an interactive dashboard

---

## 🙌 Author

**Anand Patidar**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
