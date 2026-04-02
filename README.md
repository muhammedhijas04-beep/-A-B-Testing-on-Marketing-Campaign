# 📊 A/B Testing on Marketing Campaign

## 🚀 Overview

This project analyzes and compares the performance of two marketing campaigns (Control vs Test) using A/B testing techniques. The goal is to determine which campaign performs better based on engagement, conversion efficiency, and cost effectiveness.

The analysis follows a complete data workflow:

* Data cleaning
* Feature engineering
* Exploratory analysis
* Statistical testing
* Visualization
* Business recommendation

---

## 🎯 Objective

To identify the better-performing campaign by evaluating:

* User engagement (CTR)
* Conversion efficiency (Conversion Rate)
* Cost efficiency (CPA)

---

## 📁 Dataset

The dataset consists of two groups:

* **Control Campaign (A)**
* **Test Campaign (B)**

### Features:

* Spend
* Impressions
* Reach
* Clicks
* Searches
* View Content
* Add to Cart
* Purchase

📌 Note: Data is aggregated (daily level), not user-level.

---

## ⚙️ Methodology

### 1. Data Cleaning

* Loaded raw CSV files
* Cleaned column names and formats
* Converted data types
* Handled missing values
* Merged control and test datasets

---

### 2. Feature Engineering

Created key performance metrics:

* **CTR (Click Through Rate)** = Clicks / Impressions
* **Conversion Rate** = Purchases / Clicks
* **Add to Cart Rate** = Add to Cart / Clicks
* **CPC (Cost per Click)** = Spend / Clicks
* **CPA (Cost per Acquisition)** = Spend / Purchases

📌 Insight: Raw counts are less meaningful than ratios for performance evaluation.

---

### 3. Exploratory Analysis

Comparison between control and test campaigns:

* Test campaign → higher CTR (better engagement)
* Control campaign → higher conversion rate (better funnel quality)
* Control campaign → lower CPA (better cost efficiency)

---

### 4. Statistical Testing

A **Z-test for proportions** was used to determine if the difference in conversion rates is statistically significant.

#### Hypothesis:

* H0: No difference between campaigns
* H1: Significant difference exists

#### Result:

* Z-stat ≈ 11.83
* p-value ≈ 0

📌 Conclusion: The difference is statistically significant (not due to chance).

---

### 5. Visualization

Key visualizations include:

* CTR comparison
* Conversion rate comparison
* CPA comparison
* Marketing funnel analysis

#### Funnel Stages:

Impressions → Clicks → Add to Cart → Purchase

📌 Insight:
The control campaign retains more users across the funnel, while the test campaign shows higher drop-off after clicks.

---

## 🔍 Key Insights

* Higher CTR does not guarantee better performance
* Test campaign attracts more users but lower-quality traffic
* Control campaign converts users more efficiently
* Control campaign achieves lower cost per acquisition
* Statistical testing confirms results are reliable

---

## ✅ Final Recommendation

The **Control Campaign** is the better-performing strategy because:

* Higher conversion efficiency
* Lower acquisition cost
* Stronger funnel performance
* Statistically validated results

👉 Recommended Action:

* Scale the control campaign
* Optimize the test campaign (targeting, messaging, landing page)

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Statsmodels

---

## 📌 Project Structure

```
ab-testing-marketing-campaign/
│
├── notebooks/
│   └── ab_testing_analysis.ipynb
├── visuals/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📈 What This Project Demonstrates

* End-to-end A/B testing workflow
* Data-driven decision making
* Statistical hypothesis testing
* Marketing funnel analysis
* Business-focused insights

---

## 🔥 Key Takeaway

> Performance is not just about attracting users — it’s about converting them efficiently and minimizing acquisition cost.

---

## 👤 Author

**Muhammed Hijas**

---

## ⭐ If you found this useful

Feel free to star ⭐ the repository!

