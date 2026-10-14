# 🛒 Ecommerce Sales Dashboard (Power BI)

An interactive **Power BI** dashboard that analyzes ecommerce sales performance across time, geography, product categories, payment modes, and customers. It helps answer questions like *Which products make the most profit? Which states drive the most revenue? How do sales trend month over month?*

---

## 📌 Project Overview

| Item | Details |
|------|---------|
| **Tool** | Microsoft Power BI Desktop |
| **File** | `Ecommerce_Sales_Dashboard.pbix` |
| **Data Model** | 2 tables – `Orders` and `Details` |
| **Report Pages** | 1 (single-page dashboard) |
| **Theme** | Blue gradient background with custom title |

---

## 📊 Dashboard Features

### Key Performance Indicators (KPI Cards)
- 💰 **Total Amount** (Sales)
- 📦 **Total Quantity** sold
- 📈 **Total Profit**
- 🧾 **Average Order Value (AOV)**

### Visualizations
| Visual | What it shows |
|--------|---------------|
| **Column chart** | Profit by month (order date) |
| **Bar chart** | Profit by product sub-category |
| **Donut chart** | Quantity sold by category |
| **Donut chart** | Quantity sold by payment mode |
| **Bar chart** | Sales amount by state |
| **Column chart** | Sales amount by customer |

### Interactive Filters (Slicers)
- 📅 **Quarter** (from Order Date hierarchy)
- 📍 **State**

All visuals are cross-filtered, so selecting a quarter or state updates the whole dashboard.

---

## 🗂️ Data Model

The model consists of two related tables:

**`Orders`**
- Order Date (with date hierarchy: Year / Quarter / Month / Day)
- State
- Customer Name

**`Details`**
- Amount
- Profit
- Quantity
- Category
- Sub-Category
- Payment Mode
- AOV (Average Order Value measure)

---

## 🔍 Key Insights You Can Draw

**Headline numbers:** 438K total sales amount · 5,615 units sold · 37K total profit

- 📍 **Top states:** Maharashtra leads in sales, followed by Madhya Pradesh, Uttar Pradesh, Delhi and Rajasthan.
- 👕 **Clothing dominates** the product mix, making up 63% of quantity sold (Electronics 21%, Furniture 17%).
- 🖨️ **Most profitable sub-categories:** Printers, Bookcases, Saree, Accessories and Tables.
- 📅 **Profit is seasonal:** January–March and November are the strongest months, while May, July, September and December show losses.
- 💳 **Cash on Delivery is the most popular payment mode (44%)**, followed by UPI (21%), Debit Card (13%), Credit Card (12%) and EMI (10%).
- 🧑 **Top customers** by sales include Harivansh, Madhav and Madan Mohan.

---

## 🚀 How to Use

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/brohit25820060-ctrl/Ecommerce-Sales-Dashboard.git
   ```
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. Open `Ecommerce_Sales_Dashboard.pbix`.
4. Use the **Quarter** and **State** slicers to explore the data.

> 💡 If Power BI asks you to refresh data, make sure the source files are available at the original path or update the data source under **Home → Transform data → Data source settings**.

---

## 🛠️ Skills Demonstrated

- Data modeling & table relationships
- DAX measures (e.g., AOV)
- Data visualization & dashboard design
- Interactive reporting with slicers
- Business/sales analytics

---

## 📁 Repository Structure

```
├── Ecommerce_Sales_Dashboard.pbix   # Power BI report
├── README.md                        # Project documentation
└── screenshots/                     # (Optional) dashboard preview images
```

---


## 👤 Author

**brohit25820060-ctrl**
- GitHub: [@brohit25820060-ctrl](https://github.com/brohit25820060-ctrl)

---

⭐ If you found this project helpful, please consider giving it a star!
