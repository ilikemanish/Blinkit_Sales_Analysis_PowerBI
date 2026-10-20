
<p align="center">
  <img src="ICONS/blinkit_logo.png" alt="Blinkit Logo" width="300"/>
</p>

<h1 align="center">📊 Blinkit Sales & Outlet Performance Dashboard</h1>

<p align="center">
  <img src="https://img.shields.io/badge/TOOL-POWER%20BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/LANGUAGE-DAX%20%7C%20POWER%20QUERY-00B4D8?style=for-the-badge&logo=microsoft&logoColor=white" alt="DAX and Power Query"/>
  <img src="https://img.shields.io/badge/PROJECT-DATA%20ANALYSIS-54B226?style=for-the-badge" alt="Data Analysis"/>
  <img src="https://img.shields.io/badge/DOMAIN-QUICK%20COMMERCE-FF4B4B?style=for-the-badge&logo=shopify&logoColor=white" alt="Quick Commerce"/>
</p>

---

## 📌 Project Overview

The **Blinkit Sales & Outlet Performance Dashboard** is a business intelligence project developed using Microsoft Power BI.

The dashboard analyzes Blinkit's grocery sales data to explore sales performance, outlet establishment trends, outlet sizes, outlet locations, item types, fat content, customer ratings, and item visibility.

The project demonstrates how Power BI can transform raw grocery sales data into meaningful analytical insights and actionable business recommendations.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- 🛒 Analyze total sales and average sales.
- 📦 Measure the number of items and average customer rating.
- 🥑 Analyze sales by item fat content.
- 🍎 Identify top-performing item categories.
- 🏪 Compare sales across outlet sizes and outlet locations.
- 📅 Track outlet establishment trends over time.
- 🏬 Compare outlet types across multiple performance metrics.
- 👁️ Evaluate item visibility as an operational KPI.
- 💡 Generate actionable business recommendations.

---

## 📁 Dataset Information

| Attribute | Details |
|---|---|
| Dataset | BlinkIT Grocery Data |
| Source File | `BlinkIT Grocery Data.xlsx` |
| Dashboard File | `Blinkit Analysis.pbix` |
| Tool | Microsoft Power BI Desktop |
| Languages | DAX and Power Query |
| Analysis Type | Exploratory and Business Analysis |
| Domain | Retail, Grocery, and Quick Commerce |
| Focus | Sales and Outlet Performance |

---

## 🗂️ Data Model & Analytical Structure

The dashboard uses a central **BlinkIT Grocery Data** entity and a **Metrics** field parameter to switch between KPI views.

| Area | Fields / Role |
|---|---|
| Core Entity | BlinkIT Grocery Data |
| Metric Selector | Metrics |
| Sales Measures | Total Sales, Avg Sales |
| Volume / Assortment | No. of Items |
| Customer Signal | Avg Rating |
| Product Dimensions | Item Type, Item Fat Content |
| Outlet Dimensions | Outlet Type, Outlet Size, Outlet Location Type |
| Time Dimension | Outlet Establishment Year |
| Operational Field | Item Visibility |

---

## 🛠️ Tools & Technologies

- 📊 Microsoft Power BI
- 💻 DAX (Data Analysis Expressions)
- 🔄 Power Query
- 📈 Data Modeling
- 📉 Interactive Visualizations
- 🎛️ Field Parameters
- 📋 KPI Cards and Slicers
- 🔍 Exploratory Data Analysis

---

## 📊 KPI Framework

The dashboard provides a compact KPI layer to summarize overall sales performance and customer ratings.

| KPI | Dashboard Value | Business Question |
|---|---:|---|
| Total Sales | $1.20M | How much sales revenue is represented in the current view? |
| Avg Sales | $141 | What is the average sales value? |
| No. of Items | 8,523 | How many items are represented? |
| Avg Rating | 3.9 | What is the overall customer rating? |

---

## 📈 Business Analysis

### 1️⃣ Product & Sales-Mix Analysis

**Business Question:** Where are sales concentrated by fat content and item type?

**Concepts Used:** Donut Chart, Bar Chart, and Sales Share Analysis.

#### Sales by Fat Content

| Fat Content | Sales | Share |
|---|---:|---:|
| Low Fat | $425.36K | 35.4% |
| Regular | $776.32K | 64.6% |

#### Top Item Types by Sales

| Item Type | Sales |
|---|---:|
| Fruits & Vegetables | $0.18M |
| Snack Foods | $0.18M |
| Household | $0.14M |
| Frozen Foods | $0.12M |
| Dairy | $0.10M |
| Canned | $0.09M |
| Baking Goods | $0.08M |
| Health & Hygiene | $0.07M |
| Meat | $0.06M |
| Soft Drinks | $0.06M |

**Key Insight:** Regular-fat products account for the larger share of displayed sales. Fruits & Vegetables and Snack Foods lead the item-type ranking at approximately $0.18M each.

**Follow-up Question:** Are high-sales categories also delivering stronger ratings, average sales, and item visibility, or is revenue concentration hiding operational opportunities?

---

### 2️⃣ Outlet Size, Location & Establishment Analysis

**Business Question:** How do outlet size, location, and establishment trends relate to sales performance?

**Concepts Used:** Donut Chart, Funnel Chart, Line Chart, and Segmentation.

#### Sales by Outlet Size

| Outlet Size | Sales | Share |
|---|---:|---:|
| Small | $248.99K | 20.7% |
| Medium | $507.90K | 42.3% |
| High | $444.79K | 37.0% |

#### Sales by Outlet Location Tier

| Location Tier | Sales | Share |
|---|---:|---:|
| Tier 1 | $336.40K | 28.0% |
| Tier 2 | $393.15K | 32.7% |
| Tier 3 | $472.13K | 39.3% |

#### Outlet Establishment Trend

The line chart shows a visible sales peak around 2018, at approximately $205K, with lower values before and after the peak.

**Key Insights:**

- Medium outlets contribute the largest share among the displayed outlet-size segments.
- Tier 3 locations contribute the largest share among the displayed location tiers.
- The establishment trend highlights a peak around 2018.

**Business Question:** What operational or market factors explain the differences between outlet sizes, location tiers, and establishment years?

---

### 3️⃣ Outlet-Type Performance Analysis

**Business Question:** How do outlet types perform across multiple KPIs?

**Concepts Used:** Matrix, Multi-Metric Comparison, and KPI Analysis.

| Outlet Type | Total Sales | No. of Items | Avg Sales | Avg Rating | Item Visibility |
|---|---:|---:|---:|---:|---:|
| Grocery Store | $151.94K | 1,083 | $140 | 4.00 | 0.10 |
| Supermarket Type1 | $787.55K | 5,577 | $141 | 4.00 | 0.06 |
| Supermarket Type2 | $131.48K | 928 | $142 | 4.00 | 0.06 |
| Supermarket Type3 | $130.71K | 935 | $140 | 4.00 | 0.06 |

**Key Observation:** Supermarket Type1 is the dominant displayed outlet format, contributing approximately $787.55K, or 65.5%, of the shown sales mix.

**Operational Insight:** Comparing sales, item volume, average sales, customer ratings, and item visibility together provides a broader view of outlet performance than revenue alone.

---

## 🧠 DAX & Power BI Concepts Used

### 🔹 Basic Power BI

- KPI Cards
- Slicers
- Donut Charts
- Bar Charts
- Line Charts
- Funnel Charts
- Matrix Visuals

### 🔹 Advanced Power BI

- Field Parameters
- Dynamic Metric Selection
- DAX Measures
- Calculated Columns
- Data Modeling
- Interactive Filters
- Cross-Filtering

### 🔹 DAX Functions

- `SUM()`
- `AVERAGE()`
- `COUNT()`
- `DIVIDE()`
- `CALCULATE()`
- `FILTER()`
- `ALL()`
- `SWITCH()`

---

## 📋 Analysis Areas

| Area | Analysis |
|---|---|
| 🛒 Sales | Total Sales and Avg Sales |
| 📦 Volume | Number of Items |
| ⭐ Ratings | Average Customer Rating |
| 🥑 Fat Content | Low Fat vs. Regular |
| 🍎 Item Types | Top-Selling Categories |
| 🏪 Outlet Size | Small, Medium, and High |
| 🌍 Outlet Location | Tier 1, Tier 2, and Tier 3 |
| 📅 Establishment | Year-wise Sales Trends |
| 🏬 Outlet Type | Grocery Store vs. Supermarkets |
| 👁️ Visibility | Item Visibility Analysis |

---

## 💡 Key Analytical Insights

The analysis highlights the following patterns:

- 📊 Regular-fat products account for approximately 64.6% of displayed sales.
- 🏪 Medium outlets represent approximately 42.3% of sales by outlet size.
- 🌍 Tier 3 locations contribute approximately 39.3% of sales by location tier.
- 🏬 Supermarket Type1 contributes approximately 65.5% of the displayed outlet-type sales.
- 🍎 Fruits & Vegetables and Snack Foods are the leading item categories.
- 📅 The establishment trend shows a peak around 2018 at approximately $205K.
- ⭐ The average rating of 3.9 provides a customer satisfaction benchmark.

*These findings describe the supplied dashboard figures and should be interpreted in the context of the selected filters and source data.*

---

## 🏗️ Dashboard Architecture & User Flow

The dashboard follows a left-to-right analytical workflow, moving from filtering and KPIs to detailed comparisons.

| Filters | KPI Strip | Analysis | Segmentation | Detail |
|---|---|---|---|---|
| Outlet Location Type | Total Sales | Fat Content | Outlet Size | Outlet-Type Matrix |
| Outlet Size | Avg Sales | Item Type | Outlet Location | Item Visibility |
| Item Type | No. of Items | Establishment Trend | Outlet Type | Performance Comparison |
| — | Avg Rating | — | — | — |

### User Journey

1. Filter the data by business segment.
2. Review the headline KPIs.
3. Identify the strongest product and outlet segments.
4. Inspect location and size patterns.
5. Validate performance using the outlet-type matrix.
6. Convert observations into business recommendations.

---

## 💡 Business Recommendations

1. **Optimize Product Assortment**

   Investigate the sales contribution of leading item categories and compare it with customer ratings and item visibility.

2. **Compare Outlet Performance**

   Evaluate outlets by sales, item volume, average sales, ratings, and visibility rather than relying on sales alone.

3. **Investigate Location Differences**

   Explore the reasons behind stronger sales contributions from Tier 3 locations.

4. **Review Establishment Trends**

   Investigate the factors associated with the sales peak around 2018 before making expansion decisions.

5. **Improve KPI Monitoring**

   Use consistent definitions for total sales, average sales, item counts, ratings, and visibility.

6. **Support Data-Driven Decisions**

   Use interactive filters and field parameters to investigate business questions from multiple perspectives.

---

## 📂 Repository Structure

```text
Blinkit_Sales_Analysis_PowerBI/
│
├── README.md
├── ICONS/
│   └── blinkit_logo.png
├── BlinkIT Grocery Data.xlsx
├── Blinkit Analysis.pbix
├── Blinkit_Analysis_Project_Report.pdf
└── Final_Dashboard.jpg
```

---

## 🚀 How to Run the Project

### Step 1: Open Power BI Desktop

Launch Microsoft Power BI Desktop on your computer.

### Step 2: Open the PBIX File

Open `Blinkit Analysis.pbix` from the downloaded repository.

### Step 3: Explore the Dashboard

Use the available filters to analyze:

- Outlet Location Type
- Outlet Size
- Item Type

### Step 4: Switch KPIs

Use the **Metrics** field parameter to switch between:

- Total Sales
- Avg Sales
- No. of Items
- Avg Rating

### Step 5: Review the Results

Analyze the charts, KPI cards, and matrix to understand sales patterns and outlet performance.

---

## 📄 Project Files

| File | Description |
|---|---|
| `Blinkit Analysis.pbix` | Interactive Power BI dashboard |
| `BlinkIT Grocery Data.xlsx` | Source dataset |
| `Blinkit_Analysis_Project_Report.pdf` | Detailed project report |
| `Final_Dashboard.jpg` | Dashboard preview image |
| `ICONS/blinkit_logo.png` | Project logo |

---

## 🖼️ Dashboard Preview

<p align="center">
  <img src="Final_Dashboard.jpg" alt="Blinkit Sales and Outlet Performance Dashboard" width="100%"/>
</p>

### Dashboard Components

- 🎛️ **Filter Panel:** Outlet Location Type, Outlet Size, and Item Type
- 📊 **KPI Cards:** Total Sales, Avg Sales, Number of Items, and Avg Rating
- 🍩 **Donut Charts:** Fat Content and Outlet Size
- 📊 **Bar Charts:** Item Type and Fat Content by Outlet
- 📈 **Line Chart:** Outlet Establishment Trend
- 🔺 **Funnel Chart:** Outlet Location
- 📋 **Matrix:** Outlet Type, Sales, Items, Avg Sales, Rating, and Visibility

---

## 🎓 Skills Demonstrated

- 📊 Power BI Dashboard Development
- 💻 DAX Calculations and Measures
- 🔄 Data Modeling and Relationships
- 🎛️ Field Parameters and Metric Switching
- 📈 Interactive Data Visualization
- 🧹 Data Cleaning and Transformation
- 📋 KPI Design and Business Reporting
- 💡 Analytical Thinking and Insight Generation

---

## 👨‍💻 Author

**Manish Kashyap**

🎯 Aspiring Data Analyst  
📊 SQL | Excel | Python | Power BI | Data Analytics  
🤖 AI and Machine Learning Enthusiast

---

## 🔗 Connect With Me

- **GitHub:** [ilikemanish](https://github.com/ilikemanish)
- **Portfolio:** [Visit My Portfolio](https://portfolio-ci5f.vercel.app/)

---

⭐ **If you find this project useful, consider giving the repository a star!**

Built with **Power BI & DAX** 💛📊

<p align="center">
  <b>🛒 Blinkit — India's Last Minute App 🛒</b>
  <br/>
  <i>Data-Driven Decisions for Quick Commerce</i>
</p>
