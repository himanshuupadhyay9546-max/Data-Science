# 📁 Month-1 Internship Repository
## Python Basics & Data Manipulation

This repository contains all tasks, projects, and documentation completed during **Month‑1** of my Data Science / Python Internship.

---

# 🗂️ Repository Structure

```
Month-1-Internship/
│
├── README.md
├── Internship_Report_Month-1.md
│
├── Week-1_Python_Basics/
│   ├── temperature_converter.py
│   ├── calculator.py
│   └── average_temperature_project.py
│
├── Week-2_Data_Structures_Functions/
│   ├── sum_of_squares.py
│   ├── filtering_lambda.py
│   ├── factorial_recursion.py
│   └── data_cleaning_project.py
│
├── Week-3_NumPy_Pandas/
│   ├── numpy_operations.py
│   ├── broadcasting_example.py
│   ├── pandas_dataframe.py
│   └── dataset_cleaning_project.py
│
└── Week-4_Data_Visualization/
    ├── line_plot.py
    ├── histogram.py
    ├── heatmap.py
    └── visualization_dashboard.py
```

---

# 📄 README.md

```md
# Python Internship — Month 1

This repository contains the work completed during Month‑1 of my internship, focusing on:

- Python Programming Basics
- Data Structures & Functions
- NumPy & Pandas
- Data Visualization

## 🔧 Tools & Technologies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

## 📅 Weekly Breakdown

### Week 1 — Python Basics
- Temperature Converter
- Calculator
- Average Temperature Project

### Week 2 — Data Structures & Functions
- Sum of Squares
- Lambda Filtering
- Recursion
- Data Cleaning Script

### Week 3 — NumPy & Pandas
- Array Operations
- Broadcasting
- DataFrames
- Dataset Cleaning

### Week 4 — Data Visualization
- Line Plot
- Histogram
- Heatmap
- Visualization Dashboard

---

👨‍💻 Author: Himanshu Kumar Upadhyay
```

---

# 📄 Internship_Report_Month-1.md

```md
# Internship Report — Month 1

## Introduction
Month‑1 focused on Python fundamentals, data manipulation, and visualization.

## Objectives
- Learn Python basics
- Work with data structures
- Use NumPy & Pandas
- Create visualizations

## Weekly Summary

### Week 1
Learned variables, loops, conditionals and built basic scripts.

### Week 2
Worked with functions, recursion, and data cleaning.

### Week 3
Performed dataset manipulation using NumPy & Pandas.

### Week 4
Built charts and dashboards using Matplotlib & Seaborn.

## Skills Gained
- Python Programming
- Data Cleaning
- Data Analysis
- Visualization

## Conclusion
The first month built a strong foundation for advanced data science learning.
```

---

# 🧠 WEEK 1 FILES

## temperature_converter.py
```python
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
kelvin = celsius + 273.15

print("Fahrenheit:", fahrenheit)
print("Kelvin:", kelvin)
```

## calculator.py
```python
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("1.Add 2.Subtract 3.Multiply 4.Divide")
choice = int(input("Choose operation: "))

if choice == 1:
    print(num1 + num2)
elif choice == 2:
    print(num1 - num2)
elif choice == 3:
    print(num1 * num2)
elif choice == 4:
    print(num1 / num2)
else:
    print("Invalid")
```

## average_temperature_project.py
```python
temps = []
n = int(input("How many readings? "))

for i in range(n):
    temps.append(float(input("Enter temperature: ")))

print("Average:", sum(temps)/n)
```

---

# 🧠 WEEK 2 FILES

## sum_of_squares.py
```python
def sum_of_squares(nums):
    return sum(x**2 for x in nums)

print(sum_of_squares([1,2,3,4]))
```

## filtering_lambda.py
```python
nums = [10,15,20,25,30]
evens = list(filter(lambda x: x%2==0, nums))
print(evens)
```

## factorial_recursion.py
```python
def fact(n):
    if n<=1:
        return 1
    return n*fact(n-1)

print(fact(5))
```

## data_cleaning_project.py
```python
data = [10,20,20,30,40]
unique = list(set(data))
filtered = [x for x in unique if x>20]

print(unique)
print(filtered)
```

---

# 🧠 WEEK 3 FILES

## numpy_operations.py
```python
import numpy as np
arr = np.array([10,20,30])
print(np.mean(arr))
print(arr**2)
```

## broadcasting_example.py
```python
import numpy as np
arr = np.array([1,2,3])
print(arr+5)
```

## pandas_dataframe.py
```python
import pandas as pd

data = {"Name":["A","B"],"Marks":[80,90]}
df = pd.DataFrame(data)
print(df)
```

## dataset_cleaning_project.py
```python
import pandas as pd

data = {"Marks":[80,None,75]}
df = pd.DataFrame(data)
print(df.fillna(df.mean()))
```

---

# 🧠 WEEK 4 FILES

## line_plot.py
```python
import matplotlib.pyplot as plt
plt.plot([1,2,3],[10,20,30])
plt.show()
```

## histogram.py
```python
import matplotlib.pyplot as plt
plt.hist([50,60,70,80,90])
plt.show()
```

## heatmap.py
```python
import seaborn as sns
import pandas as pd

data = pd.DataFrame([[1,2],[3,4]])
sns.heatmap(data,annot=True)
```

## visualization_dashboard.py
```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.DataFrame({
    "Age":[20,21,22],
    "Marks":[70,80,90]
})

plt.scatter(df["Age"],df["Marks"])
plt.show()
```

---

# ✅ How to Upload on GitHub

1. Create new repository → `Month-1-Internship`
2. Upload all folders & files
3. Add README.md
4. Commit → Push

---

If you want, I can next create:
- Month‑2 repository
- PPT presentation
- Internship portfolio repo

