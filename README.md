# Calories Burned Analysis: Gender and Age Impact on   Calories Burned.

## 1. Introduction

This project explores the relationship between the number of calories burned, gender, and age.
The goal is to understand whether these demographic factors affect how many calories people burn during physical activity.

Key questions:

* Do males and females burn calories at different rates?
* Does age influence calories burned?

The analysis uses data visualization and statistical testing to identify meaningful patterns and insights.

---

## 2. Data Exploration and Description

The dataset is loaded and checked for missing values, data types, and summary statistics.

**Dataset:** Final_data.csv
**Columns:**

* Age: Age of the individual
* Gender: Male or Female
* Calories Burned: Number of calories burned during activity

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')

file_path = "/kaggle/input/life-style-data/Final_data.csv"
df = pd.read_csv(file_path)
```

---

## 3. Analysis Overview

* Visualized the relationships between age, gender, and calories burned
* Measured correlation strength
* Conducted statistical tests to check significance

---

## 4. Key Findings

* Age and calories burned have a very weak correlation (−0.02)
* Gender and calories burned show no significant difference (P-value = 0.88)
* Visuals confirm no strong relationship between these factors

---

## 5. Conclusion

The analysis suggests that neither age nor gender significantly affects calories burned.
Other factors, such as workout intensity, body weight, and fitness level, likely play a larger role.

---

## 6. Tools and Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

SciPy




