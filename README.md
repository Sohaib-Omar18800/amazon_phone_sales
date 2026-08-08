<div align="center">

# 📱 Amazon Phone Sales Analysis

### Interactive Business Intelligence Dashboard built with Power BI

<br>

<img src="screenshots/Home%20Page.png" alt="Amazon Phone Sales Dashboard" width="950">

<br><br>

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)](https://powerbi.microsoft.com/)
[![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/power-query/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-orange?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![Excel](https://img.shields.io/badge/Excel-Data%20Source-green?style=for-the-badge&logo=microsoftexcel)](https://www.microsoft.com/en-us/microsoft-365/excel)

</div>

---

## 📊 About the Project

This project presents an interactive **Amazon Phone Sales Dashboard** built with **Microsoft Power BI** to analyze mobile phone sales performance across different brands and products.

The goal was to transform raw sales data into an interactive business intelligence solution that makes it easier to monitor key performance indicators, compare brands, identify sales patterns, and explore product-level details.

The dashboard combines **data preparation, data modeling, DAX calculations, KPI development, and interactive visualization** into a single reporting solution.

---

## 🎯 Business Objectives

The dashboard was designed to answer key business questions such as:

- Which brands generate the highest sales volume?
- How does average price relate to sales volume?
- Which brands receive the highest share of ratings?
- Which products and brands demonstrate strong performance?
- What are the overall sales and rating KPIs?
- How can users move from high-level performance to detailed product analysis?

---

## 📌 Key Performance Indicators

<div align="center">

| Metric | Value |
|:---|---:|
| 📦 **Total Sold Volume** | **130.8K** |
| 💰 **Average Price** | **171.83** |
| ⭐ **Average Rating** | **4.08 / 5** |
| 📊 **Average Sales Volume** | **484.44** |
| 🏆 **Amazon Best Sellers** | **2** |

</div>

---

# 🔍 Key Insights

### 1. Price vs. Sales Volume

The analysis suggests a **general inverse relationship between average price and sales volume** among the leading brands.

**Alcatel** achieved the highest average sales volume at **750 units**, while having one of the lowest average prices at **47.9**.

On the other hand, **OnePlus**, with an average price of approximately **408**, recorded an average sales volume of **414 units**.

However, the relationship is not strictly linear. Mid-priced brands such as **iPhone** and **Panasonic** also achieved strong sales volumes.

> **Key takeaway:** Lower-priced brands tend to achieve higher sales volumes in the analyzed data, but price alone does not fully explain sales performance.

---

### 2. iPhone Leads Brand Rating Share

**iPhone** accounts for the largest share of brand ratings at **36%**, followed by:

- **Samsung — 25%**
- **AT&T — 24%**
- **Motorola — 10%**
- **Panasonic — 5%**

This makes iPhone the leading brand in terms of rating share within the analyzed dataset.

---

### 3. iPhone Combines Strong Sales Volume with High Ratings

iPhone recorded:

- **Average Sales Volume:** 661
- **Average Price:** 192
- **Average Rating:** 4.28
- **Rating Share:** 36%

This places iPhone **second in average sales volume** while also having the largest share of brand ratings.

This combination makes iPhone one of the strongest-performing brands in the analyzed dataset.

---

### 4. Top Brands by Sales Volume

The leading brands by average sales volume are:

| Rank | Brand | Average Price | Average Sales Volume |
|:---:|:---|---:|---:|
| 🥇 | **Alcatel** | 47.9 | **750** |
| 🥈 | **iPhone** | 192 | **661** |
| 🥉 | **Panasonic** | 101 | **617** |
| 4 | **Samsung** | 250 | **571** |
| 5 | **AT&T** | 60.2 | **521** |
| 6 | **Motorola** | 137 | **480** |

---

# 📈 Dashboard Pages

## 🏠 1. Home Page

The Home page provides a high-level overview of the analysis and acts as the main navigation point for the report.

Users can select a brand from the interactive visuals to explore additional details.

<div align="center">

<img src="screenshots/Home%20Page.png" alt="Home Page" width="950">

</div>

---

## 📊 2. Metrics & KPIs

The Metrics page focuses on the main business indicators, including:

- Average Price
- Total Sales Volume
- Amazon Best Sellers
- Average Rating
- Average Sales Volume
- Brand Rating Distribution

<div align="center">

<img src="screenshots/Metrics%20%26%20KPIs.png" alt="Metrics and KPIs" width="950">

</div>

---

## 📱 3. Products Analysis

The Products Analysis page provides a detailed comparison of brands based on:

- Total Sales Volume
- Average Sales Volume
- Total Brand Ratings
- Average Brand Ratings
- Average Price

It also includes interactive filtering and sorting capabilities to help users explore brand performance from different perspectives.

<div align="center">

<img src="screenshots/Products%20Analysis.png" alt="Products Analysis" width="950">

</div>

---

## 🔎 4. Drill-Through Analysis

The Drill-Through page allows users to move from high-level brand analysis into more detailed product-level information.

This enables a deeper investigation of individual products without losing the context of the overall analysis.

<div align="center">

<img src="screenshots/Drill%20Through.png" alt="Drill Through Analysis" width="950">

</div>

---

# 🔄 Data Preparation & Transformation

The project involved preparing the source data before building the Power BI report.

Main steps included:

- Data cleaning and preparation
- Transforming fields required for analysis
- Handling data types and inconsistencies
- Preparing analytical dimensions
- Creating calculated metrics
- Building relationships required for reporting
- Preparing the dataset for interactive visualization

The transformation process was mainly handled using **Power Query**, while **DAX** was used to create analytical measures and KPIs.

---

# 🧮 Data Modeling & DAX

The dashboard uses Power BI data modeling concepts to structure the data for analysis.

DAX was used to create calculated measures required for:

- Sales volume analysis
- Average calculations
- Rating analysis
- KPI cards
- Brand comparisons
- Interactive reporting

The model was designed to support dynamic filtering and cross-visual interaction throughout the report.

---

# 🎛️ Interactive Features

The dashboard includes several interactive elements designed to improve the analysis experience.

### 🔹 Brand Selection

Users can select a brand directly from the visual to explore its performance.

### 🔹 Dynamic Filters

The report includes filters for:

- Active Brands
- Active Ratings
- Best Seller status

### 🔹 Drill-Through

Users can navigate from aggregated brand-level analysis to more detailed product-level information.

### 🔹 Dynamic Sorting

The Products Analysis page allows users to switch the analysis perspective between metrics such as:

- Average Price
- Average Sales Volume

---

# 🛠️ Tools & Technologies

<div align="center">

| Technology | Purpose |
|:---|:---|
| **Microsoft Power BI** | Dashboard development & interactive reporting |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Measures, KPIs & analytical calculations |
| **Data Modeling** | Structuring data for analysis |
| **Microsoft Excel** | Source data & initial data preparation |

</div>

---

# 💡 Skills Demonstrated

Through this project, I practiced and demonstrated:

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Data Modeling
- DAX
- Power Query
- KPI Development
- Business Intelligence
- Data Visualization
- Interactive Dashboard Design
- Drill-Through Analysis
- Dynamic Filtering
- Business-Oriented Reporting
- Analytical Storytelling

---

## 👨‍💻 Author

<div align="center">

### Sohaib Omar Abdelfatah

**Data Analyst | Data Engineering Background**

<br>

<a href="https://github.com/Sohaib-Omar18800">
<img src="https://img.shields.io/badge/GitHub-Sohaib--Omar18800-181717?style=for-the-badge&logo=github">
</a>

<a href="https://www.linkedin.com/in/sohaib-omar-188oo/">
<img src="https://img.shields.io/badge/LinkedIn-Sohaib%20Omar-0A66C2?style=for-the-badge&logo=linkedin">
</a>

<a href="https://sohaib-omar18800.github.io/">
<img src="https://img.shields.io/badge/Portfolio-Visit%20Portfolio-4285F4?style=for-the-badge&logo=googlechrome">
</a>

</div>

---

<div align="center">

⭐ If you found this project useful, feel free to explore the repository.

</div>
