# 🛒 E-Commerce Customer Intelligence & Sales Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Tableau](https://img.shields.io/badge/Tableau-Public-orange)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## 📊 Live Dashboard
🔗 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/tabish.iqbal/viz/E-CommerceCustomerIntelligenceDashboards_/ECommerceRevenueOverview)

---

## 📌 Project Overview
End-to-end data analytics project analyzing **525,000+ real transactions** from a UK-based e-commerce retailer to uncover customer behaviour patterns, identify revenue risks, and segment customers using Machine Learning.

> **Key Finding:** £2,061,626 in revenue is at risk from churned and at-risk customer segments — equivalent to 23% of total revenue.

---

## 🎯 Business Problems Solved

| Problem | Approach | Finding |
|---------|----------|---------|
| Who are our best customers? | RFM Segmentation | 5 VIP Whales avg £215K spend each |
| Where is revenue at risk? | Churn Analysis | £2M from Lost + At Risk segments |
| When do customers buy most? | Time Series EDA | Q4 spike — holiday season driven |
| Where should we expand? | Geographic Analysis | Asia = zero revenue, untapped market |
| What drives sales? | Product Analysis | Top 3 products drive 35% of revenue |

---

## 🛠️ Tools & Technologies

- **Python** — Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Machine Learning** — K-Means Clustering, RFM Scoring
- **Visualization** — Tableau Public (interactive dashboard)
- **Dataset** — UCI Online Retail II (525K+ rows, real-world data)

---

## 📁 Project Structure

    ecommerce-customer-intelligence/
    │
    ├── notebooks/
    │   ├── 01_data_cleaning.ipynb
    │   ├── 02_exploratory_analysis.ipynb
    │   ├── 03_rfm_segmentation.ipynb
    │   └── 04_kmeans_clustering.ipynb
    │
    ├── data/
    │   ├── ecommerce_clean.csv
    │   └── rfm_segments.csv
    │
    ├── visualizations/
    │   ├── monthly_revenue.png
    │   ├── top_products.png
    │   ├── segments_pie.png
    │   └── kmeans_clusters.png
    │
    └── README.md

---

## 🔍 Key Insights

### 1️⃣ Revenue Trend
- Business generates **£8.83M** in annual revenue
- **86.1%** concentrated in UK market — high geographic risk
- Strong Q4 spike confirming **holiday/gifting season dependency**

### 2️⃣ Customer Segmentation (RFM + K-Means)

| Segment | Customers | Avg Spend | Action |
|---------|-----------|-----------|--------|
| VIP Whales | 5 | £215,544 | Dedicated relationship manager |
| High Value Loyalists | 59 | £28,018 | Loyalty rewards program |
| Core Customers | 3,201 | £1,711 | Regular engagement campaigns |
| Churned | 1,047 | £597 | Win-back email campaign |

### 3️⃣ Revenue at Risk

    Lost Customers:     £782,858
    At Risk Customers:  £1,278,768
    Total at Risk:      £2,061,626  (23% of total revenue)

### 4️⃣ Product Intelligence
- **White Hanging Heart T-Light Holder** — highest revenue AND quantity
- Low margin (£1.90–£3.24) but extreme volume (max 936 units/order)
- Confirms **B2B wholesale model** — avg order value £459

### 5️⃣ Geographic Opportunity
- EU markets (EIRE, Netherlands, Germany) show strong traction
- **Asia = completely untapped** despite 4.3B potential consumers
- Recommended entry points: Singapore + Japan (high income + gifting culture)

---

## 🚀 How to Run

    # Clone the repo
    git clone https://github.com/Tabish166/ecommerce-customer-intelligence

    # Install dependencies
    pip install pandas numpy matplotlib seaborn scikit-learn openpyxl

    # Run notebooks in order
    jupyter notebook

---

## 📬 Connect With Me
- 💼 [LinkedIn](https://www.linkedin.com/in/tabishiqbal100205)
- 🐙 [GitHub](https://github.com/Tabish166)
- 📧 tabishiq10@gmail.com
