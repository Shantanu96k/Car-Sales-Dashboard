# Car Sales Dashboard (Power BI)

### Project Overview
This project presents an **interactive Power BI dashboard** built to analyze car sales and resale performance.  
It helps visualize **key performance metrics**, compare brand performance, and track resale value trends over time.

### Objectives
- Analyze car sales and profitability.
- Calculate total and percentage-based profits using DAX.
- Identify top-performing manufacturers and models.
- Visualize year-wise trends and resale value patterns.
- Build an interactive dashboard with filters and KPIs for business insights.

### Key Features
- **Data Cleaning & Transformation:**  
  - Handled missing values and duplicates in Power Query.  
  - Ensured consistent formatting for better analysis.

- **DAX Measures Created:**  
  - `Total Profit = SUM('Car_sales'[__year_resale_value])`  
  - `Profit % of Total = DIVIDE(SUM('Car_sales'[__year_resale_value]), CALCULATE(SUM('Car_sales'[__year_resale_value]), ALL('Car_sales')))`  
  - Additional KPIs: Average Resale Value, Total Cars Sold, Yearly Profit Growth.

- **Interactive Visuals:**  
  - Profit by Manufacturer and Model  
  - Year-wise Resale Value Trend  
  - Top 5 Brands by Profit  
  - KPI Cards for Total Profit, Avg. Resale Value, and Sales Count  
  - Slicers for Manufacturer, Model, and Year  

- **Design Enhancements:**  
  - Custom car image background (with background removed).  
  - Consistent color scheme and layout for professional presentation.

---

### Insights Gained
- Found that certain manufacturers contribute a higher share to total profit.  
- Identified models with strong resale value performance.  
- Observed year-over-year improvement in resale values and profitability.  
- Enhanced decision-making through visual insights and comparative metrics.

---

### Tools & Technologies
- **Power BI Desktop**  
- **Excel / CSV (Data Source)**  
- **DAX (Data Analysis Expressions)**  
- **Power Query**

---

### Dataset
The dataset includes:
- Manufacturer  
- Model  
- Sales data  
- Resale values  
- Year of sale  


### Outcome
The dashboard provides a **clear visual story** of car sales performance and profitability, helping stakeholders make data-driven business decisions.
