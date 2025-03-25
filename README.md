# Global Electronics Retailer Dashboard

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Data Sources](#-data-sources)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning](#-data-cleaning)
- [Data Modelling](#-data-modelling)
  - [KPIs & Metrics](#-kpis--metrics)
  - [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)
- [Recommendations](#-recommendations)
- [Limitations](#-limitations)
- [Author](#-author)
- [License](#-license)

---

## 📌 Project Overview
Founded in 2005, Global Electronics has established itself as a leading destination for cutting-edge technology and innovative gadgets worldwide. The company specializes in diverse product categories, including audio devices, computers, home appliances, cell phones, cameras, camcorders, games, toys, TVs, and videos. This dashboard provides insights into customer behavior, revenue performance, and product trends to help stakeholders make data-driven decisions.

---

## 📊 Data Sources
The analysis is based on the following structured datasets:
- **Calendar**: Provides date-related information to support time-based analysis.
- **Customers**: Contains customer demographic data, purchasing behaviors, and segmentation details.
- **Exchange Rates**: Tracks currency exchange rates for multi-region sales analysis.
- **Products**: Includes product details such as category, brand, price, and stock levels.
- **Sales**: Contains transactional data, including product sales, revenue, discounts, and profit.
- **Stores**: Includes store locations, performance metrics, and regional segmentation.

---

## 🛠 Tools & Technologies
- **Power Query**: For data transformation, cleaning, and structuring.
- **Power BI**: For building interactive visualizations and dashboards.
- **DAX (Data Analysis Expressions)**: For advanced calculations and metrics.

---

## 🧹 Data Cleaning
During the data preparation phase, the following cleaning steps were applied:
- Handling missing and inconsistent values.
- Formatting and structuring data for seamless analysis.
- Removing duplicate records.
- Standardizing currency conversions using exchange rates.
- Ensuring correct data types for calculations.

---

## 📐 Data Modelling
The data modeling approach follows a **star schema design**:
- **Fact Table**: Sales data containing transaction-level details.
- **Dimension Tables**: Calendar, Customers, Products, Exchange Rates, and Stores.
- Relationships were created based on **Primary Keys (PK)** and **Foreign Keys (FK)** to enable efficient querying and reporting.

### 📊 KPIs & Metrics
To measure business performance, the following KPIs were tracked:
- **Number of Customers**: 15,266
- **Number of Countries**: 8
- **Total Revenue**: $6.18M
- **Total Product Cost**: $2.52M
- **Total Profit**: $3.66M
- **Profit Margin (%)**: 59%
  
![KPI1](https://github.com/user-attachments/assets/403e5f55-638e-4c85-b6d4-63b3de0df8d8)

![KPI2](https://github.com/user-attachments/assets/06768c03-a13f-4fa5-beed-6c976c53b1ea)

---

### 🔍 Exploratory Data Analysis (EDA)
EDA was conducted to identify:
- Seasonal trends and sales patterns.
- Top-performing products and brands.
- Customer buying behavior and segmentation.
- Regional performance comparisons.

---

## 📈 Key Insights
1. **Revenue Comparison Between Online and Offline Stores:**
   - Online stores outperform offline stores, highlighting the shift towards digital sales channels.
2. **Top Product Category and Leading Product Subcategory:**
   - The Camera category leads with **$19 million** in revenue (34.6% of total sales).
   - The **Desktops subcategory** has the highest revenue at **$11.9 million**.
3. **Top Brand Performance:**
   - **Adventure Works** is the top-performing brand, generating **$11.9 million** in revenue.
4. **Customer Base Distribution by Country:**
   - The **United States** has the largest customer base, followed by **Canada and Australia**.
5. **Brand Performance Over Time:**
   - Most brands peaked in 2019, but **Northwind Traders** performed best in 2018, indicating a decline.
6. **Top Customer:**
   - **Mathew Flemming** is the highest revenue-generating customer with **$62,000** in purchases.
7. **Customer Acquisition Channel:**
   - **7,506 customers** were acquired through online advertising, proving the effectiveness of digital marketing.
8. **Customer Demographics:**
   - The customer base consists of **51% males**, which can inform targeted marketing strategies.

---

## 🎯 Recommendations
1. **Expand Digital Marketing Efforts:**
   - Strengthen online advertising and SEO strategies to drive more digital sales.
2. **Capitalize on High-Performing Product Categories and Brands:**
   - Expand Camera offerings and promote Adventure Works and Desktop products through targeted campaigns.
3. **Focus on Key Markets:**
   - Strengthen presence in the **United States** and explore opportunities in **Canada and Australia**.
4. **Analyze Northwind Traders' Performance:**
   - Investigate revenue decline and develop strategies for revitalization.
5. **Nurture High-Value Customers & Implement Loyalty Programs:**
   - Reward top customers like Mathew Flemming with personalized discounts and offers.
6. **Optimize Customer Acquisition Channels:**
   - Improve the effectiveness of online advertising and explore additional channels like influencer partnerships.

---

## ⚠️ Limitations
- Data may not fully capture market trends outside the analyzed regions.
- Exchange rate fluctuations may affect revenue calculations.
- Some missing values were imputed, which could introduce minor estimation biases.

---

## ✍️ Author
**Oladosu Ibrahim Adeniyi**  
_Data Analyst | Power BI Developer | Cloud Enthusiast_  


---

## 📜 License
This project is available for educational and research purposes. For commercial use, permission is required.

---

✨ **Dashboard insights powered by Power BI!** 🚀
