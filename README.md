# Campaigns and Sales Analysis | Power BI Dashboard Project

This project presents a comprehensive analysis of ice cream sales across Danish locations for the years 2017 and 2018. Built entirely in **Power BI**, it covers key business metrics, regional performance, and promotional impact, giving decision-makers a clear view of sales trends and opportunities.

The project demonstrates advanced data modeling, DAX calculations, and interactive visualizations — tailored for real-world business insight and storytelling. It was originally created as a case study and is now shared as a portfolio piece to showcase my data analytics skills.

---

## 📂 Project Summary

**Business Case:**  
A Danish company is seeking to understand their sales performance across multiple locations and the effect of a major 2018 promotional campaign (`trn_promotion_id = 47025`).  

**Objectives:**
- Evaluate overall sales and margins
- Identify best-selling items
- Detect regional differences in sales
- Measure the impact of the 2018 promotion campaign

---

## 📁 Dataset Overview

The project is based on five CSV files:
- `transactions_2017.csv`
- `transactions_2018.csv`
- `dim_site.csv`
- `dim_product.csv`
- `dim_promotion.csv`

**Key Fields Used:**
- Transaction dates, product and site IDs
- Gross amount, VAT, cost price
- Promotion ID

> 🔐 Real data is not included due to confidentiality. Sample or simulated data can be used to explore the model.

---

## 🧱 Data Modeling

A clean **star schema** was created with:
- A unified fact table combining both years' transactions
- Dimension tables for `Site`, `Product`, and `Promotion`
- Data cleaning and transformation using Power BI Power Query

**Key calculated fields & transformations:**
- `net_sales = gross_amount - vat`
- `margin = net_sales - cost_price`
- A Boolean field for promo transactions (`is_promo`)
- Date extraction (year, month) for time-based analysis

---

## ⚙️ DAX Measures

A range of custom DAX measures were written to support the analysis, including:

- **Total Sales**
- **Sales Growth YoY**
- **Total Margin**
- **Top Selling Products by Revenue**
- **Promo vs. Non-Promo Sales**
- **Promo Sales % of Total**
- **Average Margin per Product**
- **Sales by Region and Site**

---

## 📊 Power BI Dashboard Pages

The report consists of **five interactive pages**:

### 1. **Sales Overview**
- Total sales and margin by year
- Year-over-year sales comparison
- KPI cards and dynamic filtering

### 2. **Top Selling Items**
- Product-level sales performance
- Ranking of best-selling products
- Sales and margin contribution per item

### 3. **Sales by City and Site**
- Regional breakdowns using maps and bar charts
- Site-level comparisons and performance trends

### 4. **Promo Analysis – Overview**
- Sales generated during the 2018 promotion
- Comparison to non-promo transactions
- Overall uplift in revenue and volume

### 5. **Promo Analysis – Product Focus**
- Products involved in the promotion
- Promo sales vs. regular sales per item
- Margin impact of the campaign

---

## 🔍 Key Insights

- 📈 **Sales increased significantly in 2018**, largely influenced by the promo campaign.
- 💰 The promotion (ID `47025`) drove a noticeable **uplift in product volume**, but also **reduced average margin** due to discounting.
- 🏆 A small number of products accounted for the **majority of revenue** in both years.
- 🗺️ Certain sites outperformed others, highlighting the importance of **location-based strategy**.

---

## 🧠 Skills Demonstrated

| Area                | Details                                                    |
|---------------------|------------------------------------------------------------|
| **Tools**           | Power BI, DAX, Power Query                                 |
| **Data Modeling**   | Star schema, relationship design, calculated columns       |
| **Analytics**       | KPI tracking, YoY comparison, promo performance analysis   |
| **Visualization**   | Slicers, cards, dynamic charts, geographic maps            |
| **Business Insight**| Promo ROI, product performance, regional strategies        |
| **Storytelling**    | Dashboard structure and interactive insight delivery       |

---

## 📽️ Dashboard Preview

> *(Add a screenshot or screen-recorded GIF here if available)*  
> *Coming soon: Public Power BI report preview (if data is anonymized or simulated)*

---

## 🚀 How to Run This Project

1. Clone or download this repository
2. Open the `.pbix` file using **Power BI Desktop**
3. If needed, replace the file paths to load the data from your local CSVs
4. Explore each report page using filters and slicers

---

## 🙋‍♀️ About Me

I'm **Roza**, a data scientist with a strong focus on turning complex data into clear, visual stories that drive business decisions.  
🔗 [LinkedIn](https://www.linkedin.com/](https://www.linkedin.com/in/roza-abolghasemi-584a9386/)) | 📫 [Email](r.abolghasemi1@gmail.com)

---

## 💼 For Recruiters

If you're looking for a data analyst who can:
- Design clean data models
- Build executive-ready dashboards
- Understand business goals and translate them into data-driven insights

📩 Feel free to reach out! I'm open to opportunities and excited to apply my skills in real-world settings.

---

## 📌 Notes

- Promotion campaign ID: `47025`
- No real data included in this public version
- Power BI Desktop (free) is required to view the `.pbix` file

