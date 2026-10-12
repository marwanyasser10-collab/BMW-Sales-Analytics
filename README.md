# 🚗 BMW Sales Analytics Dashboard

An interactive **Power BI dashboard** designed to analyze BMW global sales performance across countries, models, customer segments, payment methods, and time periods. The dashboard provides actionable insights through KPIs, dynamic visuals, and drill-down filters.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Dashboard Pages](#-dashboard-pages)
- [Key Insights](#-key-insights)
- [Tech Stack](#-tech-stack)
- [Dataset](#-dataset)
- [How to Use](#-how-to-use)
- [Screenshots](#-screenshots)
- [Future Improvements](#-future-improvements)
- [Author](#-author)
- [License](#-license)

---

## 📖 Overview

The **BMW Sales Analytics Dashboard** is a business intelligence project built with **Microsoft Power BI**. It transforms raw BMW sales data into interactive visual reports, helping stakeholders understand:

- Overall sales and revenue performance
- Customer behavior and demographics
- Product (model/series) performance over time
- Channel and payment method effectiveness

---

## ✨ Features

- 📊 **3 Interactive Report Pages** with unified navigation
- 🎯 **KPI Cards**: Total Sales, Gross Sales, Revenue per Customer, Discount Impact
- 🌍 **Geographic Analysis** (Map + Country-level bar charts)
- 📈 **Time-Series Analysis** (Monthly / Yearly trends)
- 👥 **Customer Segmentation** by Age Group, Gender, and Behavior
- 💳 **Payment Method & Sales Channel Analysis**
- 🚙 **Model & Series Performance Comparison**
- 🎛️ **Dynamic Slicers**: Country, Sales Channel, Date, Series, Year
- 🎨 Custom BMW-themed UI (dark mode + brand colors)

---

## 📑 Dashboard Pages

### 1️⃣ BMW Sales Overview

- **KPIs:** Total Sales (235.34M), Gross Sales (244M), Revenue per Customer (36.29), Discount Impact (3.66%)
- Total Sales by **Country** (UAE, Egypt, USA, Germany, KSA, France, UK)
- Total Sales by **Month**
- Total Sales by **Sales Channel** (Showroom, Online, Corporate Fleet Deal)
- Total Sales by **Model Name** (M8 Gran Coupe, 7 Series 760i xDrive, M5 Competition, i7 xDrive60, X6 M50i)

### 2️⃣ Customer & Sales Behaviour

- **KPIs:** Total Customers (250), ML Accuracy (56.33%), High Value Sales (22.83%), Satisfaction Risk Rate (39.23%)
- Total Sales by **Payment Method** × **Sales Channel**
- Total Sales by **Customer Age Group** (Adult, Mature, Young, Senior)
- Total Sales by **City** (World Map)
- Total Sales by **Model** (Top 15 models ranked)

### 3️⃣ Product & Time Analysis

- Total Sales by **Category** (Sedan, SUV, Coupe, SUV Coupe, Hatchback, Convertible)
- Total Sales by **Gender** (Male 49.43% | Female 50.57%)
- **Gross Sales by Month** (area chart)
- Total Sales by **Series** (7 Series, 5 Series, 3 Series, X5, M8, i7)

---

## 💡 Key Insights

- 🏆 **UAE** is the top-performing country by total sales.
- 🚙 **Sedan** category dominates total sales volume.
- 🛒 **Showroom** sales channel generates **68.65%** of total sales.
- 👥 **Mature** customers contribute the highest share of sales (**35.95%**).
- 📅 Sales peak around **June–August** and **December**.
- 💳 **Installment Plan** is the most used payment method.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI** | Dashboard development & visualization |
| **Power Query (M)** | Data cleaning & transformation |
| **DAX** | Calculated measures & KPIs |
| **Bing Maps / Azure Maps** | Geographic visualization |
| **CSV / Excel** | Data source |

---

## 📂 Dataset

The dataset includes sales records with the following fields:

- `Order ID`, `Date`, `Country`, `City`
- `Model`, `Series`, `Category`
- `Customer Age Group`, `Gender`
- `Sales Channel`, `Payment Method`
- `Total Sales`, `Gross Sales`, `Discount`, `Quantity`

> 📝 *Note: The dataset is either synthetic or anonymized for demonstration purposes.*

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/marwanyasser10-collab/BMW-Sales-Analytics.git
Open the .pbix file using Power BI Desktop (free download from Microsoft).

Refresh the data if needed:

Go to Home → Refresh

Update the data source path if you moved the dataset.

Interact with the dashboard:

Use the Slicers (Country, Sales Channel, Date, Series, Year) to filter data.

Click any visual to cross-filter other visuals.

Navigate between pages using the top buttons.

🖼️ Screenshots
Page 1 — BMW Sales Overview
https://screenshots/overview.png

Page 2 — Customer & Sales Behaviour
https://screenshots/customer.png

Page 3 — Product & Time Analysis
https://screenshots/product.png

🔮 Future Improvements
□ Add forecasting using Power BI's built-in analytics.
□ Integrate real-time data via Power BI Service.
□ Add RLS (Row-Level Security) for role-based access.
□ Improve ML Accuracy by refining the prediction model.
□ Publish dashboard to Power BI Service for web access.
👤 Author
Marwan Yasser

GitHub: @marwanyasser10-collab

LinkedIn: Marwan Yasser

Email: marwanyasser010@gmail.com

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

⭐ If you found this project useful, don't forget to give it a star!
