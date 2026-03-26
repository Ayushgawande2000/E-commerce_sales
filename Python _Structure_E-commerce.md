Python Structure

📁 Python-Ecommerce-Analysis

&#x20;┣ 📄 analysis.py

&#x20;┣ 📄 dataset.csv

&#x20;┣ 📄 questions.md

&#x20; VISUALIZATION

&#x20;┗ 📄 README.md

**IMPORT LIBRARIES**

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

**LOAD DATASET**

df = pd.read\_csv("dataset.csv")

df.head()

**QUESTIONS OF PYTHON PROJECT** 

1.Total sale by region 

2.monthly sales trend

3.profit margin by category

4.top 5 customers

5.discount impact on profit 

6.high sales but low profit cities

7.top product per category

8.running total sales 

9.payment mode analysis

10.loss-making products

11.customer contribution %

12.category-wise quantity sold

13.customer with orders greater than 5 and revenue greater than 100000.

**VISUALIZATION AFTER QUESTION** 

1. monthly sales trend chart:-

**df.groupby("Month")\["Sales"].sum().plot()**

**plt.title("Monthly Sales Trend")**

**plt.show()**

**2.Discount vs profit scatter:-**

**plt.scatter(df\["Discount"], df\["Profit"])**

**plt.xlabel("Discount")**

**plt.ylabel("Profit")**

**plt.title("Discount vs Profit")**

**plt.show()**



