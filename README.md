# Customer-Shopping-Behavior-Data-Analyst-Portfolio-Project 🛒📊
An end-to-end data analytics project analyzing 3,900 customer transactions using Python (Pandas) for ETL, PostgreSQL for business logic queries, and Power BI for interactive dashboard visualization.

## 📌 Project Overview
This project provides a comprehensive analysis of customer shopping behavior using a transactional dataset of **3,900 purchases**. The goal is to uncover actionable insights into customer demographics, spending patterns, product preferences, and subscription retention to guide strategic business growth.

The project showcases a complete data pipeline: from **Python-based ETL** and **PostgreSQL database integration** to advanced **SQL analytical querying** and **Power BI dashboard building**.

---

## 🛠️ Tech Stack

| Phase | Tools & Libraries |
| :--- | :--- |
| **Data Cleaning & ETL** | Python, Pandas |
| **Database Management** | PostgreSQL |
| **Business Intelligence** | Power BI |

---

## 📊 Dataset Insights
* **Dataset Size:** 3,900 rows × 18 columns.
* **Core Metrics:** 
  * Total Customers: **3.9K**
  * Average Purchase Amount: **\$59.76**
  * Average Review Rating: **3.75**
* **Data Cleaning Note:** Successfully handled 37 missing values in the Review Rating column using category-based median imputation.

---

## ⚙️ Project Pipeline

### Phase 1: Data Preparation & ETL (Python)
1. **Exploratory Data Analysis (EDA):** Profiled dataset structure using `df.info()` and summary statistics with `.describe()`.
2. **Data Cleaning:** Imputed missing ratings and dropped redundant `promo_code_used` column.
3. **Feature Engineering:**
   * Generated `age_group` categories through age binning.
   * Created `purchase_frequency_days` tracker.
4. **Database Migration:** Connected Python directly to **PostgreSQL** to load the cleaned dataset automatically.

### Phase 2: Structured Analytics (SQL)
Executed 10 critical business logic queries in PostgreSQL, including:
* **Demographic Revenue Split:** Male customers generated the highest total revenue (\$157,890) compared to Female customers (\$75,191).
* **Customer Segmentation:** Grouped consumer base into *Loyal* (3,116), *Returning* (701), and *New* (83) segments.
* **Product Performance:** Ranked top products by category (e.g., Clothing, Accessories, Footwear) and identified items highly dependent on discounts.

### Phase 3: Interactive Visualizations (Power BI)
Designed a professional **Customer Behavior Dashboard** to track visual trends:
* Revenue and order trends across different age brackets (Young Adult, Adult, Middle-aged, Senior).
* Core operational KPIs including subscription ratios (27% Yes / 73% No) and shipping methods.

---

## 💡 Strategic Recommendations
* **Scale Subscriptions:** Introduce premium perks to convert the 73% non-subscriber majority.
* **Retention Campaigns:** Focus marketing efforts on the high-value "Loyal" segment (3,116 customers) to maximize customer lifetime value.
* **Optimize Margins:** Monitor discount-heavy items (like Hats and Sneakers) to balance promotional boosts with profit safety.
