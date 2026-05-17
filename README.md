# 🚗 Cars Data Analysis Using Python & Pandas

## 📌 Project Overview

This project focuses on analyzing a cars dataset using Python and Pandas in Jupyter Notebook. The project includes data cleaning, preprocessing, filtering, grouping, and visualization to gain meaningful insights from car-related data.

The analysis helps in understanding different car brands, fuel types, mileage, engine specifications, transmission types, and pricing trends using Exploratory Data Analysis (EDA) techniques.

---

# 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

# 📚 Libraries Used

## 🔹 Pandas

```python id="0gbm1a"
import pandas as pd
```

Used for data manipulation, filtering, cleaning, and analysis.

---

## 🔹 NumPy

```python id="dlv55p"
import numpy as np
```

Used for numerical operations.

---

## 🔹 Matplotlib

```python id="mjmyca"
import matplotlib.pyplot as plt
```

Used for charts and visualizations.

---

## 🔹 Seaborn

```python id="75wdb8"
import seaborn as sns
```

Used for advanced graphical analysis.

---

# 📂 Dataset Information

The dataset contains information related to different cars, including:

- Car Brand  
- Model  
- Type  
- Origin  
- Engine Size  
- Cylinders  
- Horsepower  
- Mileage  
- Weight  
- Wheelbase  
- Length  
- MSRP and Invoice Price  

The dataset helps in analyzing car performance, specifications, and pricing patterns.

---

# 📊 Key Operations Performed

- Data Cleaning and Preprocessing  
- Handling Missing Values  
- Filtering and Sorting Data  
- Grouping Data using `groupby()`  
- Statistical Analysis  
- Brand-wise Analysis  
- Fuel Type Analysis  
- Data Visualization using Charts and Graphs  

---

# 🔍 Questions & Tasks Performed

## ✅ Q1. Find and Handle Null Values

Checked all null values in the dataset using:

```python id="w8w1dk"
car.isnull().sum()
```

Filled missing values using:

```python id="d5bbh4"
car = car.fillna(0)
```

This helped in cleaning the dataset for further analysis.

---

## ✅ Q2. Check Different Types of Car Brands (Make)

Used value counts to identify all unique car brands and their occurrence count.

```python id="d6f5hm"
car['Make'].value_counts()
```

This analysis showed the frequency of each car manufacturer in the dataset.

---

## ✅ Q3. Filter Records Based on Origin

Displayed all records where the car origin is Asia or Europe.

```python id="11wjwq"
car[car['Origin'].isin(['Asia','Europe'])]
```

This helped in region-based filtering and analysis.

---

## ✅ Q4. Remove Records Where Weight is Above 4000

Filtered out heavy vehicles from the dataset.

```python id="12i1yl"
car[~(car['Weight'] > 4000)]
```

This operation helped in removing unwanted records for analysis.

---

## ✅ Q5. Increase MPG_City Values by 3

Applied a function to increase all city mileage values by 3.

```python id="2iwy2g"
car['MPG_City'] = car['MPG_City'].apply(lambda x:x+3)
```

This task demonstrated the use of functions on dataframe columns.

---

# 📈 Project Objectives

- Analyze real-world cars datasets  
- Understand car pricing and performance trends  
- Perform exploratory data analysis using Python  
- Visualize fuel type and brand-wise patterns  
- Improve practical knowledge of Pandas and data analytics  

---

# 📊 Sample Analysis Tasks

- Finding the most expensive cars  
- Comparing fuel types and mileage  
- Analyzing transmission types  
- Brand-wise price analysis  
- Identifying high-performance cars  
- Filtering cars based on conditions  

---

# 🎯 Learning Outcomes

Through this project, I improved my understanding of:

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Pandas Operations  
- Data Filtering and Grouping  
- Applying Functions using `apply()`  
- Handling Missing Values  
- Data Visualization  
- Working with Real-World Datasets  

---

# 📁 Project Structure

```bash id="g8s9lz"
Cars-Data-Analysis/
│
├── Cars_Data_Analysis.ipynb
├── cars_dataset.csv
├── README.md
```

# 📚 Conclusion

This project demonstrates how Python and Pandas can be used to analyze real-world cars datasets effectively. It showcases practical data analysis techniques including data cleaning, filtering, grouping, handling missing values, and applying functions on columns.
The project also improved practical skills in exploratory data analysis and helped in understanding car specifications and pricing trends using Python.

---

# ⭐ Author

**Tadi Rishitha**  
Aspiring Data Analyst | Python | Pandas | SQL | Power BI | Excel
