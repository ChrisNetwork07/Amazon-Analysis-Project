📦 Amazon Product Review Analysis (DSA PROJECT)

**RetailTech Insights – Junior Data Analyst Portfolio Project**

This project provides a comprehensive analysis of Amazon product data using Excel. The aim is to generate actionable insights that support product optimization, marketing strategies, and customer engagement improvements.


## 📁 Project Overview

- **Client:** RetailTech Insights (E-commerce Analytics Firm)
- **Objective:** Analyze product metadata and customer reviews to uncover pricing strategies, discount patterns, and high-performance products.
- **Tool Used:** Microsoft Excel (Pivot Tables, Charts, Calculated Columns, Dashboard)
- **Dataset:** Scraped Amazon product page data for 1,465 unique products


## 🧾 Dataset Description

The dataset contains the following attributes:
- **Product metadata:** Product ID, Name, Category, Product Type
- **Pricing fields:** Actual Price, Discounted Price, Discount Percentage
- **Ratings:** Rating Score (`Rate`), Rating Count
- **Engineered columns:**
  - `Price Range` — Categorized as Cheap, Mid-Range, Expensive
  - `Potential Revenue` — Estimated as `Actual Price × Rating Count`
  - `Rating (>or<50%)` — Indicates discount classification
  - `Review Count` — Classified into `<1000` or `More Than 1000`


## 📊 Analysis Tasks Completed

| # | Task |
|--|------|
| 1 | Calculated **average discount %** by product category |
| 2 | Counted number of products per **category** |
| 3 | Aggregated **total number of reviews** per category |
| 4 | Identified **top-rated products** |
| 5 | Compared **average actual price vs discounted price** |
| 6 | Highlighted **products with most reviews** |
| 7 | Counted **products with ≥50% discounts** |
| 8 | Created a **distribution chart of product ratings** |
| 9 | Computed **potential revenue** by category |
| 10 | Categorized products by **price range buckets** |
| 11 | Analyzed **correlation between rating and discount** |
| 12 | Counted **products with fewer than 1,000 reviews** |
| 13 | Highlighted **categories with highest max discounts** |
| 14 | Identified **top 5 products by combined rating × reviews** |


## 📈 Key Insights

- **64%+ discounts** are common in accessories but do not always correlate with higher ratings.
- **Expensive items** contribute significantly to potential revenue despite being fewer.
- **Top revenue contributors** include products like boAt Deuce USB Cable and Ambrane Fast Chargers.
- Most products fall within the **cheap and mid-range** pricing buckets.
- Products with **fewer than 1,000 reviews** are limited, offering opportunity for targeted promotion.

---

## 📌 Visualizations & Dashboard

Created in the **"Dashboard"** sheet:
- Bar charts for average discounts, rating distributions
- Pie chart for price range segmentation
- Highlighted KPIs and filters for category-specific insights

![image alt](https://github.com/ChrisNetwork07/Amazon-Analysis-Project/blob/main/Amazon%20Dash.PNG)

![image alt](https://github.com/ChrisNetwork07/Amazon-Analysis-Project/blob/main/Amazon%20Dash.PNG)












  


## 💡 Recommendations

- **Amplify top performers** with high ratings and review counts through featured listings or ads.
- Use **dynamic discounting** on products where higher discounts lead to improved ratings.
- **Explore underperforming categories** with high discount but poor ratings for product improvement.
- Promote **products in the mid-price range** to balance volume and revenue generation.


## 🛠 How to Use This Project

1. **Open [Cleaned Amazon case study.xlsx](https://docs.google.com/spreadsheets/d/1RnhjlamwiphRwz8Sq62wguBF2Rg0VlE7/edit?usp=drive_link&ouid=110169533604601907570&rtpof=true&sd=true)**
2. Explore the following sheets:
   - **Cleaned** – Fully prepped data
   - **Pivot and Visuals** – Tables for each analysis task
   - **Dashboard** – Summary charts and metrics
3. Use slicers/filters to explore different product categories or price ranges


## 📂 File Structure

```
├── Cleaned Amazon case study.xlsx
│   ├── amazon                # Raw data
│   ├── Cleaned               # Processed & categorized data
│   ├── Pivot and Visuals     # Calculations & aggregations
│   └── Dashboard             # Summary KPIs & charts
```


## 👤 Author

**Christopher Oriade**  
Junior Data Analyst | Excel & E-commerce Data Projects  
📧 [oriadechristopheradekunle@gmail.com]


## 📄 License

This project is for educational and portfolio purposes.
