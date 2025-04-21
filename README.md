# 🛒 Market Basket Analysis with Python

This project is my first hands-on implementation of **Market Basket Analysis** using Python. It explores how to extract meaningful association rules from transactional retail data using the **Apriori algorithm**.

---

## 📌 Project Overview

Market Basket Analysis (MBA) is a data mining technique used to identify patterns or associations between items in large transactional datasets. This technique is commonly used by retailers to optimize product placement, create targeted promotions, and improve recommendation systems.

In this project, I used a **coffee shop transactional dataset** to identify frequently co-purchased items and generate association rules based on metrics like support, confidence, and lift.

---

## ⚙️ Tools & Technologies

- **Python**
- **Pandas** – Data manipulation
- **MLxtend** – Frequent itemset and association rule mining
- **Matplotlib / Seaborn** – Data visualization
- **Jupyter Notebook**

---

## 📈 Key Techniques

- **Apriori Algorithm** to find frequent itemsets
- **Association Rule Mining**
- Analysis of:
  - **Support** – Frequency of itemsets
  - **Confidence** – Strength of implication
  - **Lift** – Strength compared to random co-occurrence

---

## 🧠 Example Insight

> **Rule:** Latte, Matcha Bun → Croissant  
> **Confidence:** 0.75  
> **Lift:** 1.30

This implies that customers who purchase a **Latte** and a **Matcha Bun** are 1.3x more likely to also buy a **Croissant**.

# 📚 Future Work

    Visualize rules as a network graph using networkx

    Develop a basic item-item recommendation engine

    Expand to customer-level analysis and time-based patterns

    Integrate customer segmentation with basket insights



# Citations

https://365datascience.com/tutorials/python-tutorials/market-basket-analysis/

https://medium.com/@baktihusen/e-commerce-insights-market-basket-analysis-using-python-efe171002b30
