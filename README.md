# 📊 E-Commerce Sales Dashboard (Power BI)

An interactive Power BI dashboard analyzing 2016 e-commerce sales across three product categories: **Men's Fashion**, **Beauty & Grooming**, and **Kids & Baby**. It covers sales trends, top products, discount impact, payment preferences, and order status breakdowns.

> 📸 *Add a screenshot here:* `![Dashboard Overview](images/overview.png)`

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Dashboard Pages](#-dashboard-pages)
- [Key Metrics](#-key-metrics)
- [Key Insights](#-key-insights)
- [Dataset](#-dataset)
- [Tools & Technologies](#-tools--technologies)
- [How to Use](#-how-to-use)
- [Repository Structure](#-repository-structure)
- [Author](#-author)

---

## 🎯 Project Overview

The goal of this project is to give business stakeholders a clear view of:

- Which categories drive the most revenue
- How sales trend over time (weekly and by working date)
- Which products (SKUs) perform best in each category
- Whether discounts influence total sales
- Which payment methods customers prefer
- How orders break down by status (complete, canceled, refunded)

A date slicer (**07/01/2016 – 12/12/2016**) lets users filter every visual on the report.

---

## 🗂 Dashboard Pages

| Page | Description |
|------|-------------|
| **Overview** | Total sales by category, total sales by start of week, and individual sales trends for each category |
| **Men's Fashion Analysis** | Key metrics, top 10 products, discount impact, payment methods, order status, sales trend |
| **Beauty & Grooming Analysis** | Key metrics, top 10 products, discount impact, order status, sales by bill type (High / Normal) |
| **Kids & Baby Analysis** | Key metrics, top 10 products, discount impact, order status, payment method breakdown |

---

## 📈 Key Metrics

| Category | Total Sales | Customers | Products Sold |
|----------|-------------|-----------|---------------|
| Men's Fashion | 5.65M | 2.12K | 2.02K |
| Beauty & Grooming | 2.30M | 1.02K | 699 |
| Kids & Baby | 789.72K | 550 | 429 |

---

## 💡 Key Insights

- **Men's Fashion is the largest category**, generating roughly 5.65M in sales, well ahead of Beauty & Grooming (2.30M) and Kids & Baby (789.72K).
- **Cash on delivery (COD) dominates payments** in Men's Fashion, accounting for about 4.27M (75.58%) of sales.
- **Completed orders make up about 46% (Men's), 58% (Beauty), and 54% (Kids)** of sales, while a significant share is canceled or refunded in every category.
- **Beauty & Grooming** sales split between *High* (1.30M) and *Normal* (1.00M) bill types.
- Each category page includes a discount-amount vs. total-sales view to explore how discounting relates to revenue.

> ⚠️ *Review these insights against your own data and adjust the wording as needed.*

---

## 🗃 Dataset

- **Period covered:** 2016 (date filter: 07/01/2016 – 12/12/2016)
- **Main fields used:** `Category Name`, `Bill Total`, `sku`, `discount_amount`, `payment_method`, `status`, `Working Date`, customer and product counts
- **Source:** *Add the dataset source / link here*

---

## 🛠 Tools & Technologies

- **Power BI Desktop**: data modeling, DAX measures, and visualization
- **Power Query**: data cleaning and transformation
- **DAX**: calculated measures (e.g., total sales, % of grand total by status)

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. **Open the report** in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (`.pbix` file).
3. **Refresh the data** if prompted, and update the data source path if needed.
4. Use the **date filter** and click on visuals to cross-filter and explore each category.

A static export of the dashboard is also available as a PDF: [`Dashboard.pdf`](Dashboard.pdf).

---

## 📁 Repository Structure

```
├── Dashboard.pbix        # Power BI report file
├── Dashboard.pdf         # Static PDF export of the dashboard
├── data/                 # Dataset (or link to source)
├── images/               # Dashboard screenshots
└── README.md
```

*Adjust to match your actual files.*

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://linkedin.com/in/your-profile)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
