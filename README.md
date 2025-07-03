# KMeans Player Clustering – Football Data Science Project

🎓 This project was developed as part of a postgraduate assignment for Machine Learning. It explores the use of **KMeans clustering** to identify distinct playing styles among **midfielders** in Europe's top leagues, using **Wyscout** data from the **2023–2024 season**.

---

## 📌 Project Overview

The goal is to group midfielders based on performance metrics in order to uncover tactical roles and behavioral patterns. This approach can support **scouting**, **player comparison**, etc.

---

## 🛠 Tools Used

- Python  
- Jupyter Notebook

---

## 📁 Data

- Source: **Wyscout**
- Season: **2023–2024**
- Leagues: **Big 5 European**
- Position: **Midfielders**
- Sample: **>1800 minutes played**

---

## 🔎 Methodology

### 1. Data Cleaning & Preprocessing

- Filtered out irrelevant columns (e.g. birth country, age, contract, etc.)
- Removed players with low playing time to reduce noise
- Selected meaningful performance indicators based on domain knowledge

### 2. Feature Engineering

- Standardized numerical features  
- Chose key metrics for clustering (passes, duels, recoveries, etc.)  
- Removed highly correlated or redundant variables

### 3. Clustering via KMeans

- Applied the KMeans algorithm to segment midfielders into **clusters**
- Used the Elbow Method and Silhouette Score to determine optimal cluster count
- Visualized player groups via PCA

---

## 📊 Insights

- Each cluster represents a **distinct player profile**:
  - E.g., deep-lying playmakers, box-to-box midfielders, defensive anchors, etc.
- Some clusters showed higher passing volume, others stood out in duels or recoveries
- Clustering revealed stylistic roles that go beyond simple stats like goals or assists

---

## 📎 Applications

- Scouting / recruitment  
- Player comparison & profiling

---

👤 **Author**: Nikolaos Georgiadis  
📅 **Date**: April 2025  
🔗 For feedback or collaboration, feel free to connect on [LinkedIn](https://www.linkedin.com/in/nikosgeorg/)

