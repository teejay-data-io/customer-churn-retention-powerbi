# 📡 Customer Retention Analytics | Power BI Dashboard

**Why are telecom customers leaving, who is leaving, and what does it cost?**

An end-to-end Power BI project: raw customer data → Power Query → DAX measures → a two-page interactive dashboard. It analyses churn and retention for a telecom provider in **California**: **7,043 customers** over one quarter (Q3), with their contracts, services, charges, satisfaction scores and the reasons churned customers gave for leaving.

📂 Part of my portfolio: [github.com/teejay-data-io](https://github.com/teejay-data-io)

**Page 1: Executive Overview**

![Customer Retention Analytics: Executive Overview page](Dashboard%201.png)

**Page 2: Customer Retention Analysis**

![Customer Retention Analytics: Customer Retention Analysis page](Dashboard%202.png)

---

## 🧰 Tools used

- **Power BI Desktop**: KPI cards, 100% stacked, bar, column, donut and scatter charts, slicers (Contract, Payment Method, Tenure Group, Offer, Internet Type) and tooltips
- **Power Query (M)**: CSV import, headers, explicit data types for all 61 columns
- **Data modelling**: dedicated measures table (40 DAX measures), sort-by columns, segmentation columns
- **DAX**: CALCULATE, DIVIDE, DISTINCTCOUNT, COUNTROWS, RANKX, ALLSELECTED, ISINSCOPE, SWITCH
- **Data validation**: duplicate and null checks, every KPI card reconciled to the source file

---

## 📊 Key metrics

| KPI | Value |
|---|---|
| Total Customers | **7,043** |
| Churned Customers | **1,869** |
| Churn Rate | **26.5%** |
| Retention Rate | **73.5%** |
| Monthly Charges Lost to Churn | **$139,131** (30.5% of monthly billing, ≈ $1.67M a year) |
| Average Customer Lifetime Value | **$4,400** |
| High-Risk Active Customers | **96** (1.9% of 5,174 active) |

---

## 💡 Key findings

1. **One in four customers left.** 1,869 of 7,043 customers churned (26.5%), taking $139,131 a month with them.
2. **Contract type is the strongest driver.** Month-to-month customers churn at 45.8%, vs 10.7% (one year) and 2.5% (two year), and make up 88.6% of all churners.
3. **Churn happens early.** 55.5% of churners left within their first 12 months.
4. **Fiber Optic is the problem product.** Fiber customers churn at 40.7% (vs 18.6% for DSL) and account for 78.2% of monthly revenue lost; Fiber on a month-to-month contract churns at 58.8%.
5. **Competitors, not price, win the customers.** 45.0% of churners left for a competitor; price was 11.3%.
6. **Add-ons protect retention.** Churn falls from 43.2% with one add-on to 5.1% with all seven.
7. **San Diego is a hotspot.** It churns at 64.9% and alone accounts for 9.9% of all churn.

📄 **Full write-up** (business problems, dataset, methodology, all findings, 10 recommendations): [PROJECT_WRITEUP.md](PROJECT_WRITEUP.md)

---

## 📁 Files

| File | What it is |
|---|---|
| `Customer Retention Analytics.pbix` | The Power BI report (open with Power BI Desktop) |
| `telco.csv` | Customer dataset (7,043 rows, 61 columns, from Kaggle) |
| `Dashboard 1.png`, `Dashboard 2.png` | Dashboard screenshots |
| `PROJECT_WRITEUP.md` | Full project write-up |

---

## 👤 Author

**Tajudeen Olugbenga Rabiu** | Data Analyst · Power BI · SQL · Python · Excel

- 💼 LinkedIn: [linkedin.com/in/tajudeen-rabiu-data](https://www.linkedin.com/in/tajudeen-rabiu-data)
- 📧 Email: [tjrabiu.data@gmail.com](mailto:tjrabiu.data@gmail.com)
- 🌐 Portfolio site: [teejay-data-io.github.io](https://teejay-data-io.github.io/)

📂 Part of my portfolio: [github.com/teejay-data-io](https://github.com/teejay-data-io)
