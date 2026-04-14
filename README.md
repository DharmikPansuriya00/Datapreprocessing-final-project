# 📊 Customer Data Pipeline & Transaction Analysis Project

## 📌 Overview

This project builds a **complete data pipeline** for customer and transaction data, including preprocessing, feature engineering, and exploratory analysis.

It integrates multiple data formats (CSV, SQL, JSON) to generate **business insights** and understand customer behavior.

---

## 🔁 Project Workflow

```id="wf9d3a"
Raw Data → 🧹 Cleaning → ⚙️ Feature Engineering → 🔗 Integration → 📊 Analysis → 💡 Insights
```

---

## 📂 Project Structure

```id="9j3a1p"
.
├── customers.csv
├── processed_customer_data.csv
├── feature_pipeline.ipynb
├── products.sql
├── transactions.json
└── README.md
```

---

## 🧩 Data Sources

| 📁 Dataset     | 📄 Format | 📌 Description                           |
| -------------- | --------- | ---------------------------------------- |
| Customers      | CSV       | Raw customer data                        |
| Products       | SQL       | Product details (price, category, stock) |
| Transactions   | JSON      | Purchase records with payment & quantity |
| Processed Data | CSV       | Cleaned + feature-engineered dataset     |

---

## ⚙️ Work Done in Notebook (feature_pipeline.ipynb)

### 🧹 Data Cleaning

* ✔️ Handled missing values
* ✔️ Removed duplicates
* ✔️ Converted data types
* ✔️ Standardized column names

---

### ⚙️ Feature Engineering

* ➕ Total spending per customer
* 🔁 Purchase frequency
* 📦 Quantity-based metrics
* 📊 Aggregated customer-level features

---

### 🔗 Data Integration

* 🔄 Merged Customers + Transactions
* 🔄 Joined Transactions + Products
* 🧱 Created unified dataset

---

### 📊 Exploratory Data Analysis (EDA)

* 📈 Summary statistics
* 🔥 Correlation heatmap
* 📉 Distribution plots
* 📊 Category-wise sales analysis

---

### 🔄 Data Transformation

* 🔤 Encoding categorical variables
* 📏 Feature scaling (if applied)

---

## 📊 Key Insights

| 🔍 Insight              | 📌 Finding                    |
| ----------------------- | ----------------------------- |
| 💰 High-value Customers | Identified top spenders       |
| 🛍️ Popular Products    | Electronics & Audio dominate  |
| 💳 Payment Trends       | UPI & Cards widely used       |
| 📈 Revenue Trends       | Seasonal variations observed  |
| 👥 Behavior Patterns    | Frequent vs occasional buyers |

---

## 🛠️ Tech Stack

| 🧰 Category   | 🚀 Tools            |
| ------------- | ------------------- |
| Language      | Python              |
| Libraries     | Pandas, NumPy       |
| Visualization | Matplotlib, Seaborn |
| Database      | SQL                 |
| Environment   | Jupyter Notebook    |

---

## 🚀 How to Run

### 1️⃣ Clone Repository

```id="s1w3qe"
git clone <repo-link>
cd project-folder
```

### 2️⃣ Install Dependencies

```id="f2j8kl"
pip install pandas numpy matplotlib seaborn
```

### 3️⃣ Run Notebook

```id="z9x1cv"
jupyter notebook
```

### 4️⃣ Execute Pipeline

```id="pl8k3m"
feature_pipeline.ipynb
```

---

## 📈 Output

* ✅ Clean dataset → `processed_customer_data.csv`
* ✅ Feature-engineered dataset
* ✅ Visual insights

---

## 🔮 Future Scope

* 🤖 Customer Segmentation (K-Means / RFM)
* 📊 Sales Prediction Model
* 🎯 Recommendation System
* 📉 Dashboard (Power BI / Streamlit)

---

## 👨‍💻 Author

**Dharmik Pansuriya**
🎓 AI/ML & Data Science Student

---

## ⭐ Project Value

✨ Demonstrates:

* End-to-end data pipeline
* Real-world data preprocessing
* Multi-source integration
* Insight-driven analysis

🚀 Perfect for Data Analyst / Data Science portfolio
