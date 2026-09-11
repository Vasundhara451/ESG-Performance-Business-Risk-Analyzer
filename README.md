# ESG-Performance-Business-Risk-Analyzer
ESG and financial performance analysis using SQL, Excel and Power BI

## 📌 Project Overview

This project analyzes Environmental, Social, and Governance (ESG) performance alongside financial and operational indicators to identify sustainability performance, environmental risks, trends, and potential business implications.

The project combines **Excel, SQL, and Power BI** to transform ESG and financial data into actionable insights.

---

## 🎯 Project Objectives

- Evaluate overall ESG performance across companies and industries.
- Identify companies with high environmental risks.
- Analyze ESG performance trends over time.
- Examine the relationship between ESG performance and financial performance.
- Identify companies that may require greater ESG attention.
- Build an interactive dashboard for ESG and business performance analysis.

---

## 🛠️ Tools & Technologies

- **Excel** – Data cleaning and validation
- **PostgreSQL / SQL** – Data analysis
- **Power BI** – Interactive dashboard and visualization
- **DAX** – Emissions intensity calculation

---

## 📊 Dataset

The dataset contains company-level ESG, environmental, social, governance, operational, and financial information.

### Key variables

- ESG Overall Score
- Environmental Score
- Social Score
- Governance Score
- Carbon Emissions
- Energy Consumption
- Water Usage
- Revenue
- Profit Margin
- Growth Rate
- Market Capitalization
- Industry
- Region
- Year

**Dataset:** ESG & Financial Performance Dataset

> Note: The dataset is synthetic and is used for analytical and portfolio purposes.

---

## 🔍 Data Cleaning & Validation

The dataset contains **11,000 records** representing **1,000 companies** across **2015–2025**.

Data validation included:

- Checking missing values
- Checking duplicate Company-Year records
- Validating numerical data types
- Checking ESG score ranges
- Checking for abnormal negative values
- Reviewing categorical values such as Industry and Region

The dataset contains **1,000 missing Growth Rate values for 2015**. These were retained as blank because growth cannot be calculated without a prior-year value.

---

## 🧮 SQL Analysis

SQL was used to analyze:

- Top-performing companies by ESG score
- ESG performance by industry
- Companies with highest carbon emissions
- Companies with highest emissions intensity
- ESG performance versus profit margin
- ESG performance versus growth rate
- ESG trends over time
- Companies with comparatively low ESG performance

An emissions intensity metric was calculated as:

`Carbon Emissions / Revenue`

---

## 📈 Power BI Dashboard

The Power BI dashboard consists of two pages:

### Page 1 — ESG Performance & Business Risk Analyzer

Provides an overall view of:

- ESG performance by industry
- ESG performance trends
- Carbon emissions
- Emissions intensity
- ESG score versus profit margin
- Company, industry, region and year filtering

### Page 2 — Company ESG Deep Dive

Provides a company-level analysis of:

- Overall ESG score
- Environmental score
- Social score
- Governance score
- ESG pillar trends
- Carbon emissions
- Energy consumption
- Water usage
- Profit margin
- Growth rate

---

## 💡 Key Findings

- Finance had the highest average ESG score in the dataset at approximately **64.62**, while Transportation had the lowest at approximately **46.03**.
- Company_478 had the highest average ESG score at approximately **96.92**.
- Company_759 had the highest average absolute carbon emissions among the companies analyzed.
- Company_145 had the highest average emissions intensity.
- Average ESG performance increased from approximately **51.44 in 2015 to 57.83 in 2025**.
- Companies in the high-ESG category had a higher average profit margin than medium- and low-ESG groups.
- The correlation between ESG Overall Score and Profit Margin was approximately **0.088**, indicating a very weak positive linear relationship.

> These findings describe relationships within the dataset and should not be interpreted as evidence of causation.

---

## 📌 Business Recommendations

Based on the analysis:

- Companies with high absolute emissions should investigate their major emission sources and reduction opportunities.
- Companies with high emissions intensity should focus on improving operational efficiency and reducing emissions relative to business output.
- Lower-performing ESG companies should identify weaknesses across Environmental, Social and Governance pillars.
- ESG performance should be monitored alongside financial and operational indicators rather than evaluated in isolation.
- Companies can use ESG dashboards to identify areas requiring further investigation and prioritize sustainability initiatives.

---

## ⚠️ Limitations

- The dataset is synthetic and therefore does not represent actual company performance.
- Correlation does not establish causation.
- ESG thresholds used for category analysis are analytical thresholds created for this project and are not official ESG ratings.
- The analysis is intended for portfolio and learning purposes.

---

## 📁 Project Structure

```text
ESG-Performance-Business-Risk-Analyzer/
│
├── README.md
├── Data/
├── SQL/
├── Power BI/
