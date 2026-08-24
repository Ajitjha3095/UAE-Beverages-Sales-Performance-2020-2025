77<div align="center">

<img width="742" height="462" alt="image" src="https://github.com/user-attachments/assets/9c7a5987-ed54-41a0-8f41-9894d3c1bfb9" />



# UAE Beverages Sales Performance 2020-2025

### End-to-End BI Project — Data Extraction → Cleaning → Power BI · Tableau · Looker Studio

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-KPI%20Measures-5E5E5E?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Relationships-2F855A?style=for-the-badge)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)



> A complete end-to-end analyst portfolio project built across three industry-standard BI platforms.
> Python (Data Extraction) →Raw data → Cleaning → Modeling → Power BI · Tableau · Looker Studio

</div>

---
## Live Demos


| Platform | Link |
|---|---|
| Power BI | See `/Dashboard` folder (`.pbix` file) |
| Tableau Public | [UAE Beverages Dashboard 2020 to 2025](https://public.tableau.com/app/profile/ajit.jha/viz/UAEBeveragesDashboard2020to2025/Dashboard1) |
| Looker Studio | [Live Report](https://datastudio.google.com/s/kP61HVnefoY)|
| GitHub Repo | [UAE-Beverages-Sales-Performance-2020-2025](https://github.com/Ajitjha3095/UAE-Beverages-Sales-Performance-2020-2025) |





## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Executive Summary](#executive-summary)
- [Business Context](#business-context)
- [Business Requirements](#business-requirements)
- [Data](#data)
    - [Dataset](#dataset)
    - [Dataset Includes](#dataset-includes)
    - [Data Fields](#data-fields)
    - [Data Usage](#data-usage)
- [What the Dashboard Answers](#what-the-dashboard-answers)
    - [Revenue](#revenue)
    - [Product & Category](#product--category)
    - [Store Performance](#store-performance)
    - [Customers](#customers)
    - [Geography](#geography)
    - [Discounts](#discounts)
    - [Executive KPI Layer](#executive-kpi-layer) 
-  [KPIs & Calculations](#kpis--calculations)
   - [DAX (Power BI)](#dax-power-bi)
   - [Tableau (Calculated Fields)](#tableau-calculated-fields)
   - [Looker Studio (Calculated Fields)](#looker-studio-calculated-fields)
- [Tech Stack](#tech-stack)
- [Skills Demonstrated](#skills-demonstrated)
  - [Data Analytics](#data-analytics)
  - [Data Modeling](#data-modeling)
  - [Business Intelligence](#business-intelligence)
  - [Analytical Skills](#analytical-skills)
- [Repository Structure](#repository-structure)
- [How to Run](#how-to-run)
- [Author](#author)
- [License](#license)





##  Project Overview

Turning beverage sales data into decisions across the UAE

A Business Intelligence project focused on understanding sales performance, category contribution, store performance, customer demographics, discount behavior, and geographic opportunities across the UAE beverage market.

The analysis was developed across Power BI, Tableau, and Looker Studio, using the same business requirements and analytical framework to create consistent reporting across three BI platforms.


## Executive Summary

The business needs a simple way to answer a difficult question:

Where are we performing well, where are we losing opportunities, and what should the business do next?

This dashboard brings sales, customers, stores, categories, discounts, and locations into one analytical view.

Instead of relying on individual reports or manually comparing numbers, decision-makers can use the dashboard to move from an overall UAE view to a specific category, city, store, customer segment, or time period.

The dashboard is designed around five core areas:

Revenue · Products · Customers · Stores · Geography

## Business Context

A beverage business operating across multiple UAE locations needs visibility into both overall performance and local-level differences.

A high-level sales number alone does not explain what is driving the result.

Management needs to understand:

- Which categories are contributing most to sales?
- Which stores are performing strongly?
- Which cities represent the largest opportunities?
- How does sales performance change over time?
- Who are the main customer segments?
- Are discounts supporting sales or reducing efficiency?
- Where should management focus its attention?

This project addresses those questions through an interactive BI reporting layer.


## Business Requirements

The dashboard was designed around the following business requirements:

| Requirement            | Business Question                          | Decision Supported                  |
|------------------------|--------------------------------------------|-------------------------------------|
| Sales Monitoring       | How much are we selling?                   | Track overall performance           |
| Category Analysis      | Which categories drive sales?              | Product and inventory decisions     |
| Store Analysis         | Which stores perform best?                 | Store benchmarking                  |
| Geographic Analysis    | Which UAE cities perform best?             | Regional strategy                   |
| Customer Analysis      | Who contributes most to sales?             | Customer targeting                  |
| Discount Analysis      | What is the impact of discounts?           | Promotion strategy                  |
| Trend Analysis         | How does performance change over time?     | Planning and forecasting            |
| KPI Monitoring         | What is the current business position?     | Executive reporting                 |

---

##  Data

The dataset used in this project is publicly available on Kaggle and contains UAE beverage sales data covering **2020–2025**.

The dataset was prepared for Business Intelligence and data analytics use cases, including sales performance, product/category analysis, store performance, customer analysis, discount analysis, and geographic analysis.

###  Dataset

**Kaggle:** [UAE Beverages Sales Dataset (2020–2025)](https://www.kaggle.com/datasets/ajitjha01/sales-dataset-uae-beverages/data)

### Dataset Includes

| Area | Description |
|---|---|
| **Time** | Sales data from 2020–2025 |
| **Product** | Beverage products and categories |
| **Sales** | Sales, net sales, quantity and pricing |
| **Store** | Store and store-type information |
| **Geography** | UAE city-level information |
| **Customer** | Customer demographic information |
| **Discount** | Discount percentage applied to sales |
| **Rating** | Customer/product rating |

### Data Fields

| Column | Description |
|---|---|
| `Date` | Date of the sales transaction |
| `Year` | Year extracted from the transaction date |
| `Month` | Month of the transaction |
| `City` | UAE city where the sale occurred |
| `Store` | Store where the transaction was recorded |
| `Store_Type` | Type of store |
| `Category` | Beverage category |
| `Product_Name` | Name of the beverage product |
| `Quantity` | Number of units sold |
| `Unit_Price` | Price per unit |
| `Sales` | Gross sales value before discount |
| `Discount_%` | Discount percentage applied |
| `Net_Sales` | Sales value after discount |
| `Gender` | Customer gender category |
| `Rating` | Customer/product rating |

### Data Usage

The dataset is used as the common data source for the project's three BI implementations:

**Kaggle Dataset → Data Preparation → KPI Development → Power BI / Tableau / Looker Studio**

This approach keeps the business logic and analytical questions consistent across all three platforms.

> **Note:** The dataset is intended for educational, analytical, portfolio, and Business Intelligence purposes.

##  What the Dashboard Answers

This interactive dashboard is purpose-built to answer the most critical business questions across key dimensions:

### Revenue
- What is the **total net sales**?
- How much **quantity** has been sold?
- How is performance changing over time?
- How does the current period compare with the previous period?

### Product & Category
- Which beverage categories contribute the most to sales?
- Is revenue concentrated in a few categories?
- Which categories deserve more attention?

### Store Performance
- Which stores are leading?
- Which stores are below the overall benchmark?
- Are there meaningful performance differences between locations?

### Customers
- What does the customer mix look like?
- Which demographic group contributes the largest share of sales?

### Geography
- Which UAE cities are generating the strongest sales?
- Where are potential regional opportunities?

### Discounts
- How much discount is being given?
- How does discounting relate to sales?
- Are promotional activities generating sufficient value?

### Executive KPI Layer

The first layer of the dashboard gives management a quick, at-a-glance read of the business.

| KPI                | Purpose                                              |
|--------------------|------------------------------------------------------|
| Total Net Sales    | Measures overall realized sales                      |
| Total Quantity     | Measures sales volume                                |
| Average Rating     | Tracks average customer/product rating               |
| Total Discount     | Measures discount value                              |
| Sales Efficiency   | Provides an efficiency view of sales performance     |

> The KPI layer is intentionally kept simple: a manager should understand the current business position before exploring the detailed charts.


##  KPIs & Calculations

The dashboard uses a common KPI framework across **Power BI, Tableau, and Looker Studio**. The same business logic is maintained across platforms while adapting the syntax to each BI tool.

---

## KPI Overview

| KPI                  | Business Definition                       | Calculation         |
| -------------------- | ----------------------------------------- | ------------------- |
| **Total Net Sales**  | Total realized sales after discounts      | `SUM(Net_Sales)`    |
| **Total Quantity**   | Total quantity sold                       | `SUM(Quantity)`     |
| **Average Rating**   | Average customer/product rating           | `AVG(Rating)`       |
| **Total Discount**   | Total discount percentage values recorded | `SUM(Discount_%)`   |
| **Sales Efficiency** | Net sales as a percentage of gross sales  | `Net Sales / Sales` |

---

# DAX (Power BI)

### 1. Total Net Sales

```DAX
Total Net Sales =
SUM('UAE_Beverages'[Net_Sales])
```

### 2. Total Quantity

```DAX
Total Quantity =
SUM('UAE_Beverages'[Quantity])
```

### 3. Average Rating

```DAX
Average Rating =
AVERAGE('UAE_Beverages'[Rating])
```

### 4. Total Discount

```DAX
Total Discount =
SUM('UAE_Beverages'[Discount_%])
```

### 5. Sales Efficiency

```DAX
Sales Efficiency =
DIVIDE(
    SUM('UAE_Beverages'[Net_Sales]),
    SUM('UAE_Beverages'[Sales]),
    0
)
```

Format the result as **Percentage**.

---

## Year-over-Year (YoY) Calculations

### 6. Net Sales YoY %

```DAX
Net Sales YoY % =
VAR CurrentSales =
    [Total Net Sales]

VAR PreviousSales =
    CALCULATE(
        [Total Net Sales],
        DATEADD('Date'[Date], -1, YEAR)
    )

RETURN
    DIVIDE(
        CurrentSales - PreviousSales,
        PreviousSales,
        0
    )
```

### 7. Quantity YoY %

```DAX
Quantity YoY % =
VAR CurrentQuantity =
    [Total Quantity]

VAR PreviousQuantity =
    CALCULATE(
        [Total Quantity],
        DATEADD('Date'[Date], -1, YEAR)
    )

RETURN
    DIVIDE(
        CurrentQuantity - PreviousQuantity,
        PreviousQuantity,
        0
    )
```

### 8. Rating YoY %

```DAX
Rating YoY % =
VAR CurrentRating =
    [Average Rating]

VAR PreviousRating =
    CALCULATE(
        [Average Rating],
        DATEADD('Date'[Date], -1, YEAR)
    )

RETURN
    DIVIDE(
        CurrentRating - PreviousRating,
        PreviousRating,
        0
    )
```

### 9. Discount YoY %

```DAX
Discount YoY % =
VAR CurrentDiscount =
    [Total Discount]

VAR PreviousDiscount =
    CALCULATE(
        [Total Discount],
        DATEADD('Date'[Date], -1, YEAR)
    )

RETURN
    DIVIDE(
        CurrentDiscount - PreviousDiscount,
        PreviousDiscount,
        0
    )
```

---

# Tableau (Calculated Fields)

## 1. Total Net Sales

```Tableau
SUM([Net_Sales])
```

---

## 2. Total Quantity

```Tableau
SUM([Quantity])
```

---

## 3. Average Rating

```Tableau
AVG([Rating])
```

---

## 4. Total Discount

```Tableau
SUM([Discount_%])
```

---

## 5. Sales Efficiency

This is the calculation used in the Tableau workbook:

```Tableau
IF SUM([Sales]) = 0 THEN 0
ELSE
    SUM([Net_Sales]) / SUM([Sales])
END
```

Format as **Percentage**.

---

## 6. Selected Year Quantity

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year])
THEN
    [Quantity]
END
```

---

## 7. Previous Year Quantity

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year]) - 1
THEN
    [Quantity]
END
```

---

## 8. Quantity YoY %

```Tableau
(
    SUM([Selected Year Quantity])
    -
    SUM([Previous Year Quantity])
)
/
SUM([Previous Year Quantity])
```

---

## 9. Selected Year Net Sales

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year])
THEN
    [Net_Sales]
END
```

---

## 10. Previous Year Net Sales

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year]) - 1
THEN
    [Net_Sales]
END
```

---

## 11. Net Sales YoY %

```Tableau
(
    SUM([Selected Year Net Sales])
    -
    SUM([Previous Year Net Sales])
)
/
SUM([Previous Year Net Sales])
```

---

## 12. Selected Year Rating

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year])
THEN
    [Rating]
END
```

---

## 13. Previous Year Rating

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year]) - 1
THEN
    [Rating]
END
```

---

## 14. Rating YoY %

```Tableau
(
    AVG([Selected Year Rating])
    -
    AVG([Previous Year Rating])
)
/
AVG([Previous Year Rating])
```

---

## 15. Selected Year Discount

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year])
THEN
    [Discount_%]
END
```

---

## 16. Previous Year Discount

```Tableau
IF YEAR([Date])
   = YEAR([Parameters].[Year]) - 1
THEN
    [Discount_%]
END
```

---

## 17. Discount YoY %

```Tableau
(
    SUM([Selected Year Discount])
    -
    SUM([Previous Year Discount])
)
/
SUM([Previous Year Discount])
```

---

# Looker Studio (Calculated Fields)

### 1. Total Net Sales

```text
SUM(Net_Sales)
```

### 2. Total Quantity

```text
SUM(Quantity)
```

### 3. Average Rating

```text
AVG(Rating)
```

### 4. Total Discount

```text
SUM(Discount_%)
```

### 5. Sales Efficiency

```text
SUM(Net_Sales) / SUM(Sales)
```

---

## YoY Calculations in Looker Studio

### 6. Net Sales YoY %

When using a date dimension, the preferred approach is to use Looker Studio's **Comparison → Previous Year** option.

Conceptually:

```text
(Current Net Sales - Previous Year Net Sales)
/
Previous Year Net Sales
```

### 7. Quantity YoY %

```text
(Current Quantity - Previous Year Quantity)
/
Previous Year Quantity
```

### 8. Rating YoY %

```text
(Current Average Rating - Previous Year Average Rating)
/
Previous Year Average Rating
```

### 9. Discount YoY %

```text
(Current Discount - Previous Year Discount)
/
Previous Year Discount
```

---


This keeps the executive layer focused while allowing the detailed charts to provide the supporting analysis.

> **Note:** `Discount_%` is stored as a percentage field in the source data. The dashboard currently aggregates this field using `SUM(Discount_%)`, matching the existing Tableau implementation. For a production financial model, an **average discount rate or discount amount** would generally be a more meaningful KPI than summing percentage values.

## Tech Stack

- **BI Tools:** Power BI, Tableau Public, Looker Studio
- **Data Prep:** Python (Pandas)
- **Data Format:** CSV
- **Version Control:** GitHub

## Skills Demonstrated

### Data Analytics
- Python
- Data Extraction
- Data Cleaning
- Data Transformation
- Data Validation
- Data Preparation

### Data Modeling
- Data Modeling
- KPI Development
- Business Metrics Design
- Calculated Fields
- Data Relationships

### Business Intelligence
- Power BI
- DAX
- Tableau
- Tableau Calculated Fields
- Google Looker Studio
- Looker Studio Calculated Fields
- Interactive Dashboard Development
- Data Visualization
- Data Storytelling

### Analytical Skills
- Customer Churn Analysis
- Revenue Loss Analysis
- Customer Retention Analysis
- User Behavior Analysis
- Performance Monitoring
- Dashboard Design

## Repository Structure
## 📁 Repository Structure

```bash
UAE-Beverages-Sales-Performance/
├── Dashboard/           # Power BI (.pbix) and Tableau (.twbx) workbook files
├── Dataset/             # Source and processed CSV data files
├── Images/              # Screenshots of all three dashboards (Power BI, Tableau, Looker Studio)
├── python/              # Python scripts for data cleaning, transformation, and EDA (Pandas)
├── README.md
└── architecture.md      # Detailed data model, KPI documentation, and technical notes (optional)
```

## How to Run

### Option 1: Clone the Repository

```bash
git clone https://github.com/Ajitjha3095/UAE-Beverages-Sales-Performance-2020-2025.git
cd UAE-Beverages-Sales-Performance-2020-2025
```

Then open the required dashboard file from the `Dashboard/` folder:

- **Power BI:** Open the `.pbix` file using Power BI Desktop.
- **Tableau:** Open the `.twbx` file using Tableau Desktop or Tableau Public.
- **Python:** Run scripts from the `python/` folder.

```bash
python python/<script_name>.py
```

### Option 2: Download ZIP File

1. Open the repository:  
   [UAE Beverages Sales Performance 2020–2025](https://github.com/Ajitjha3095/UAE-Beverages-Sales-Performance-2020-2025)

2. Click **Code** → **Download ZIP**.

3. Extract the downloaded ZIP file.

4. Open the project folder.

5. Open the dashboard file from the `Dashboard/` folder:

   - Open `.pbix` files in **Power BI Desktop**.
   - Open `.twbx` files in **Tableau Desktop** or **Tableau Public**.
   - Run Python scripts from the `python/` folder.

```bash
python python/<script_name>.py
```

> Use the dashboard filters and slicers to analyze sales by year, region, beverage category, product, and sales performance.

## Author

**Ajit Jha**  
*Data Analytics & Data Engineering Portfolio Project* 

⭐ Project

If you find the analytical approach useful, feel free to explore the repository and dashboards.

- **GitHub:** [Ajitjha3095](https://github.com/Ajitjha3095)
- **LinkedIn:** [Ajit Jha](https://www.linkedin.com/in/ajitjha01/)

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
