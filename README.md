# 🚢 Titanic EDA – Exploratory Data Analysis on Passenger Survival

This project explores the famous Titanic dataset to uncover patterns in passenger survival using Python. It is a beginner-friendly EDA focused on understanding how factors like age, sex, class, and family size influenced survival chances.

---

## 📊 Objectives

- Perform univariate and bivariate analysis
- Clean and prepare data for analysis
- Visualize key trends using Seaborn and Matplotlib
- Derive insights from the Titanic disaster through data

---

## 📁 Dataset

- **Source**: `sns.load_dataset('titanic')` from Seaborn
- 891 passenger records with 15 features, including:
  - `survived`: 0 = No, 1 = Yes
  - `pclass`: Passenger class (1, 2, 3)
  - `sex`, `age`, `fare`, `embarked`, etc.

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

---

## 🧹 Data Cleaning Steps

- Handled missing values (`age`, `embarked`, etc.)
- Created a new feature: **`Family Size`** = `sibsp` + `parch` + 1
- Converted categorical data where necessary

---

## 📈 Key Visualizations

- Age distribution with survival hue
- Survival rates by `sex`, `pclass`, and `family size`
- Correlation heatmap for numerical features

---

## 🔍 Key Insights

- **Females** had a much higher survival rate than males.
- **Younger passengers** (children) were more likely to survive.
- **1st class** passengers had better survival odds than 2nd and 3rd.
- Larger families had mixed survival trends; mid-sized families did best.

---

## 🧾 Summary

This EDA showcases basic data analysis and visualization skills using Python. It highlights how human and social factors influenced survival on the Titanic and provides a foundation for further modeling or machine learning.

---

## 📌 Future Improvements

- Handle missing data more robustly
- Perform feature engineering for cabin, titles from names, etc.
- Train a logistic regression model or decision tree based on EDA

---

## 📷 Sample Outputs

![image](https://github.com/user-attachments/assets/a71ae330-4197-4e32-8577-959901709f49)


---

## 📬 Contact

Made by [Your Name] – aspiring data analyst / data scientist.  
Feel free to reach out via [Gmail](jawadism420@gmail.com).

