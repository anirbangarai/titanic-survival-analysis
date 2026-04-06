# Titanic Survival Data Analysis

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to identify the key factors that influenced passenger survival during the Titanic disaster.

The analysis explores relationships between survival and various passenger attributes such as **gender, passenger class, age, fare, and embarkation port**.

The goal of this project is to understand patterns in the dataset and extract meaningful insights using statistical analysis and data visualization.

---

## Dataset

The dataset used in this project is the **Titanic dataset from Kaggle**, which contains information about passengers aboard the RMS Titanic.

Dataset Link:
https://www.kaggle.com/competitions/titanic/data

### Dataset Features

The dataset includes the following important columns:

* **PassengerId** – Unique identifier for each passenger
* **Survived** – Survival status (0 = No, 1 = Yes)
* **Pclass** – Passenger class (1st, 2nd, 3rd)
* **Name** – Passenger name
* **Sex** – Gender of the passenger
* **Age** – Age of the passenger
* **SibSp** – Number of siblings/spouses aboard
* **Parch** – Number of parents/children aboard
* **Ticket** – Ticket number
* **Fare** – Ticket fare
* **Cabin** – Cabin number
* **Embarked** – Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## Project Workflow

1. Data Loading
2. Data Inspection
3. Handling Missing Values
4. Data Cleaning
5. Exploratory Data Analysis
6. Visualization of Survival Patterns
7. Insight Extraction

---

## Analysis Performed

The following analyses were performed:

* Distribution of passenger ages
* Survival rate by gender
* Survival rate by passenger class
* Relationship between fare and survival
* Passenger distribution across embarkation ports
* Analysis of missing values in the dataset

---

## Key Insights

* **Female passengers had a significantly higher survival rate compared to males.**
* **First-class passengers had higher survival probabilities than second and third class passengers.**
* **Younger passengers showed slightly higher survival rates.**
* Ticket fare and passenger class show a strong relationship with survival chances.

---

## Project Structure

```
titanic-survival-analysis
│
├── titanic_eda.ipynb
├── train_and_test2.csv
└── README.md
```

---

## Author

**Anirban Garai**
MSc Data Science
