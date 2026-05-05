# Titanic Data Visualization

This project explores the **Titanic dataset** using **basic EDA** and **8 different charts** in Python.

---

## 1. Dataset

- Titanic passenger data loaded from a CSV URL  
- Main columns:
  - `Survived`, `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

---

## 2. Tools

- `pandas` – data loading and cleaning  
- `matplotlib` – all plots  
- `seaborn` – correlation heatmap  

---

## 3. Basic EDA

- Look at shape, head, info, describe  
- Handle missing values:
  - Fill `Embarked` with `"S"`  
  - Fill `Age` with median (or group median)

---

## 4. Charts

1. **Line plot** – survival rate by age  
2. **Bar plot** – survival rate by sex  
3. **Pie chart** – passenger class distribution  
4. **Histogram** – age distribution (with mean and median lines)  
5. **Scatter plot** – Age vs Fare, colored by Survived  
6. **Box plot** – Fare by passenger class  
7. **Violin plot** – Age by sex  
8. **Heatmap** – correlation between numeric features

---

## 5. Skills Practiced

- Basic EDA  
- Cleaning missing values  
- Creating common plots in Python  
- Reading charts to understand survival patterns on the Titanic
