# 🚗 Coupon Acceptance Analysis

## Overview
This project explores behavioral patterns of drivers who receive location-based coupons while driving.  
Using data from the **UCI Machine Learning Repository**, we analyze which factors influence whether a driver accepts or rejects a coupon.

Scenarios include restaurants, bars, coffee houses, and takeaway food under different conditions (passengers, weather, destination, etc.).  

The final goal is to identify **what distinguishes customers who accept coupons from those who do not**.

---

## 🧠 Data Source
The dataset comes from a survey on Amazon Mechanical Turk and is available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation).

---

## 🧹 Data Preparation
1. Handle missing data using logical replacements (e.g., `never` for missing frequency categories).
2. Encode ordinal features where applicable.
3. Visualize and explore key attributes using `pandas`, `matplotlib`, and `seaborn`.

---

## 📊 Analysis Highlights
- **Overall coupon acceptance rate**
- Acceptance rate by **coupon type**
- Influence of **weather, passenger, and destination**
- Focused exploration of **bar** and **coffee house** coupons
- Summary statistics and hypotheses on acceptance behavior

---

## 💡 Key Insights
- Frequent bar-goers and coffee-house visitors are much more likely to accept those respective coupons.
- Acceptance tends to increase when driving with friends or partners (vs. alone or with kids).
- Weather and time of day show mild influence — sunny afternoons produce slightly higher acceptance rates.

---

## 📓 Notebook
You can view the full analysis in the notebook:

**[`notebooks/coupon_acceptance_analysis.ipynb`](notebooks/coupon_acceptance_analysis.ipynb)**

---

## 🛠️ Requirements
To run the notebook:

```bash
pip install -r requirements.txt
