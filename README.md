# Finance & Sales Analysis Dashboard (Power BI)

An interactive 4-page Power BI report analysing global financial transactions, customers and products. It shows how transactions perform over time, which channels and payment methods drive activity, and how customers and products contribute to overall results.

## Project Overview

| Item | Detail |
|---|---|
| Period covered | October 2022 – October 2025 |
| Transactions | 12K+ |
| Total amount | 92.28M |
| Customers | 500 |
| Accounts | 200 |
| Products | 50 |

## Tools Used

- **Power BI Desktop** – data model, visuals, navigation and filters
- **Excel** – source data (`finance_dataset_multitable.xlsx`) and preprocessing

## Dataset

The source workbook has five sheets: **Transactions, Customers, Accounts, Products, Calendar**. They are related in the Power BI data model to support analysis by customer, product, account and date.

## Dashboard Pages

1. **Home Page** – project summary, headline KPIs (Sum of Amount, customers, products, transactions) and navigation buttons.
2. **Transaction Analysis** – transaction type by amount, status split, sales by year, payment methods, channels and category trends, with Year / Currency / Region filters.
3. **Customer & Product Analysis** – top 10 customers, customer segments, product treemap, customers by year, amount by category and a category ribbon chart.
4. **Insights** – key findings and recommendations.

## Screenshots

| Home | Transaction Analysis |
|---|---|
| ![Home](<img width="1373" height="775" alt="image" src="https://github.com/user-attachments/assets/c6e60bd2-02e7-4404-bf61-c6b2f28323ff" />
) | ![Transaction Analysis](<img width="1377" height="773" alt="image" src="https://github.com/user-attachments/assets/79dba82a-341f-4f4f-83d1-5e9b7e3b6e68" />
) |

| Customer & Product Analysis | Insights |
|---|---|
| ![Customer & Product Analysis](<img width="1377" height="776" alt="image" src="https://github.com/user-attachments/assets/ee73016d-abe4-4045-9517-2a6ca2f629b0" />
) | ![Insights](<img width="1373" height="772" alt="image" src="https://github.com/user-attachments/assets/e2dc494b-bc7c-4886-bfdc-e62878bceca2" />
) |

## Key Insights

- **Transaction health:** Status is split evenly: 33.3% Completed, 33.3% Failed, 33.3% Pending. Reducing failures and clearing pending items is the biggest opportunity.
- **Chargebacks:** Chargebacks have the highest total amount (24M), slightly above Sales (23M), Fees (23M) and Refunds (23M), which points to risk in payment disputes and returns.
- **Sales trend:** Sales grew from 6.4M (2022) to 30.2M (2023) and 31.5M (2024), then fell to 24.2M in 2025. 2022 and 2025 are partial years, so the 2025 dip is not a full-year decline.
- **Channels & payments:** All four channels (InStore, MobileApp, Online, Partner) contribute equally at 92M each. Credit Card leads payment methods slightly.
- **Category:** Apparel is the top category (23M), and Food is the lowest (13M).
- **Customers:** SMB is the largest segment (182 customers, 36.4%), followed by Enterprise (160) and Retail (158).
- **Products:** The top products (Product_44, Product_39, Product_33) are separated by only a small margin, so no single product dominates revenue.

## How to Use

1. Clone or download this repository.
2. Open `Finance_Report.pbix` in Power BI Desktop.
3. Use the Year, Currency and Region slicers and the navigation buttons to explore the report.
A static PDF export is also included: `Finance_Report.pdf`.


## Author

**Habeeb Mohamed**
Aspiring Data Analyst | SQL (MySQL) · Python · Excel · Power BI
GitHub: [THEIDOL07](https://github.com/THEIDOL07) · LinkedIn: [your-profile](www.linkedin.com/in/habeeb-mohamed-77004b416)
