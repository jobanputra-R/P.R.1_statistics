# 📊 Statistics & Data Analysis Project

A professional data analysis project focused on **core statistical concepts** and their **practical implementation in Python** using a real-world household dataset.  
This repository combines **theoretical explanations**, **computational methods**, and **visualizations**, making it suitable for academic submission and GitHub presentation.

--- 
## 📁 Dataset Description

**Dataset:** `household_data.csv`

The dataset contains household-level information such as:
- Age of household head  
- Household income  
- Family size  
- Education level  
- Home ownership status  
- Urban / rural classification  

**Purpose:**  
The dataset is used to demonstrate statistical analysis techniques, including descriptive statistics, distributions, and measures of spread, supported by visualizations.

---

## 📓 Notebook Overview

### 🔹 Part A.ipynb — *Fundamentals of Statistics*

This notebook focuses on introductory statistical concepts:

**Types of Data**
- Numerical data  
- Categorical data  

**Types of Statistics**
- Descriptive statistics  
- Inferential statistics  

**Measures of Central Tendency**
- Mean  
- Median  
- Mode  

**Measures of Dispersion**
- Range  
- Variance  
- Standard Deviation  

---

### 🔹 Part B.ipynb — *Statistical Distributions & Advanced Measures*

This notebook covers advanced statistical concepts and visual interpretation:

- Gaussian (Normal) Distribution  
- Log Normal Distribution  
- Empirical Rule (3-Sigma Rule)  
- Percentiles  
- Quartiles  
- Five Number Summary  
- Skewness  
- Kurtosis  

---

## 📘 Statistical Concepts Explained

### 1️⃣ Gaussian Distribution (Normal Distribution)

A symmetric, bell-shaped distribution where most values cluster around the mean.

**Key Properties:**
- Mean = Median = Mode  
- Symmetrical about the mean  

---

### 2️⃣ Log Normal Distribution

A distribution in which the logarithm of the variable follows a normal distribution.

**Key Features:**
- Values are always positive  
- Right-skewed distribution  

---

### 3️⃣ Empirical Rule (3-Sigma Rule)

Describes data spread in a normal distribution:
- 68% of data lies within ±1σ  
- 95% of data lies within ±2σ  
- 99.7% of data lies within ±3σ  

---

### 4️⃣ Percentiles

Percentiles divide a dataset into **100 equal parts**.  
The *kth percentile* represents the value below which *k%* of observations fall.

---

### 5️⃣ Quartiles

Quartiles divide data into **four equal parts**:
- Q1 → 25th percentile  
- Q2 → 50th percentile (Median)  
- Q3 → 75th percentile  

---

### 6️⃣ Five Number Summary

A concise summary of a dataset consisting of:
- Minimum  
- First Quartile (Q1)  
- Median  
- Third Quartile (Q3)  
- Maximum  

Commonly visualized using a box plot.

---

### 7️⃣ Skewness

Measures the **asymmetry** of a distribution:
- Positive skew → longer right tail  
- Negative skew → longer left tail  

---

### 8️⃣ Kurtosis

Measures the **peakedness** of a distribution:
- Leptokurtic → sharply peaked  
- Platykurtic → flat  
- Mesokurtic → normal  

---

## 🛠️ Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---
## Images from part b
![Normal Distribution](images/normal_distribution.png)

![Household Income Across Education Levels](images/Household%20Income%20Across%20Education%20levels.png)

![Family Size by Education Level](images/boxplot%20Family%20size%20by%20education%20level.png)

## 📂 Repository Structure
```text
.
├── household_data.csv        # Dataset used for analysis
├── Part A.ipynb              # Basic statistical concepts
├── Part B.ipynb              # Distributions & advanced measures
├── images/                   # Plots and diagrams generated from analysis
│   ├── normal_distribution.png
│   ├── Household Income Across Education levels.png
│   ├── boxplot Family size by education level.png
└── README.md