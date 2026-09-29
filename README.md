
# 📊 Exploratory Data Analysis – Adult Income Dataset

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of the Adult Income dataset using Python. The main objective is to understand the structure of the dataset, clean the data, perform statistical analysis, identify patterns and relationships between variables, detect outliers, and visualize important findings.

The analysis is performed using **Pandas, NumPy, Matplotlib, Seaborn, and SciPy** in a Jupyter Notebook.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand and explore the dataset.
* Inspect rows, columns, data types, and dataset structure.
* Perform data cleaning and handle missing values.
* Perform statistical analysis on numerical columns.
* Analyze categorical variables and their frequencies.
* Calculate percentages and statistical measures.
* Identify relationships between numerical variables.
* Detect and analyze outliers.
* Use different visualization techniques to understand the data.
* Generate meaningful insights from the dataset.

---

## 📂 Dataset

The project uses the **Adult Income dataset**, which contains demographic and employment-related information about individuals.

The dataset contains:

* **32,561 rows**
* **15 columns**

### Dataset Columns

| Column           | Description                           |
| ---------------- | ------------------------------------- |
| `Age`            | Age of the individual                 |
| `Workclass`      | Type of employment/work sector        |
| `Final Weight`   | Census-related weighting value        |
| `Education`      | Education level                       |
| `EducationNum`   | Numerical representation of education |
| `Marital Status` | Marital status                        |
| `Occupation`     | Occupation of the individual          |
| `Relationship`   | Relationship status                   |
| `Race`           | Race category                         |
| `Gender`         | Gender                                |
| `Capital Gain`   | Capital gain amount                   |
| `capital loss`   | Capital loss amount                   |
| `Hours per Week` | Number of working hours per week      |
| `Native Country` | Country of origin                     |
| `Income`         | Income category (`<=50K` or `>50K`)   |

---

## 🛠️ Technologies & Libraries Used

* **Python**
* **Jupyter Notebook / Google Colab**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **SciPy** – Statistical analysis and outlier detection
* **AutoViz** – Automated data visualization

---

## 🔍 EDA Process

### 1. Data Loading

The dataset is loaded into a Pandas DataFrame and inspected to understand its structure and contents.

```python
import pandas as pd

df = pd.read_csv("adult.csv")
```

---

### 2. Data Exploration

The dataset is explored using operations such as:

* `head()`
* `tail()`
* Shape and column inspection
* Data type inspection
* Filtering
* Unique value analysis
* Frequency analysis

---

### 3. Statistical Analysis

Statistical measures are calculated for numerical columns, including:

* Count
* Mean
* Median
* Minimum
* Maximum
* Standard deviation

For example, the analysis calculates the average, median, minimum, and maximum age of individuals.

The dataset shows:

* Average age: approximately **38.58 years**
* Median age: **37 years**
* Minimum age: **17 years**
* Maximum age: **90 years**

The average working time is approximately **40.44 hours per week**.

---

### 4. Categorical Data Analysis

The project analyzes categorical variables using functions such as:

```python
value_counts()
nunique()
```

For example, the `Education` column contains **16 unique education categories**.

The `Income` column is also analyzed to understand the distribution between the two income categories.

---

### 5. Income Analysis

The income distribution was analyzed using `value_counts()`.

The dataset contains:

* **24,720 individuals** earning `<=50K`
* **7,841 individuals** ear
