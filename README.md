# Adventure Works Sales Analysis Dashboard  

## 📋 Project Overview  
This Power BI project involves creating an interactive and insightful dashboard for the company **Adventure Works**. The purpose of the dashboard is to analyze sales data for the years **2020, 2021, and 2022** to derive key business insights. Decision-makers can explore performance trends, customer behavior, product performance, and more to enable data-driven strategies.  

---

## 🗂️ Data Sources  
The project uses the following datasets:  
1. **Sales Data** (2020, 2021, 2022)  
2. **Returns Data**  
3. **Calendar Lookup**  
4. **Customer Lookup**  
5. **Territory Lookup**  
6. **Product Lookup**  
7. **Product Category Lookup**  
8. **Product Subcategory Lookup**  

---

## 🛠️ Process Flow  

### 1. **Data Cleaning**  
- Cleaned and transformed raw data using **Power Query**.  
- Ensured accurate and consistent data by addressing missing values, removing irrelevant columns, and assigning appropriate data types.  

### 2. **Data Modeling**  
- Created a **star schema** with the following tables:  
  - **Fact Table**: Sales Data, Returns Data.  
  - **Dimension Tables**: Calendar Lookup, Customer Lookup, Territory Lookup, Product Lookup, Product Subcategory Lookup, and Product Category Lookup.  
- Defined **one-to-many relationships** between fact and dimension tables based on primary and foreign keys.  

### 3. **Measures and Calculations**  
Developed a wide range of **DAX measures** for advanced calculations and insights:  
- **Aggregate Functions**:  
  - `SUM`: Total Revenue, Total Cost, Total Quantity.  
  - `SUMX`: Calculations across filtered tables (e.g., profit per product).  

- **Ranking Functions**:  
  - `RANKX`: Ranking customers, products, or regions based on metrics like revenue or profit.  

- **Filtering Functions**:  
  - `ALL`, `ALLSELECTED`, `EXCEPT`: To modify or reset filters and calculate custom aggregations.  

- **Logical and Conditional Functions**:  
  - `CALCULATE`: Used extensively for conditional measures like Sales Growth, Profit Margin, etc.  
  - `RELATED`: Pulled values from related dimension tables to enrich fact table calculations.  

---

## 🎨 Dashboard Features  
- **Interactive Visuals**: Includes bar charts, line charts, pie charts, and KPI cards.  
- **Key Influencers Analysis**:  
  - **Home Ownership**: Shows how factors like marital status, income, and education level impact home ownership likelihood.  
  - **Average Retail Price**: Examines how the sum of product costs influences average retail price.  
- **Decomposition Tree**: Drills into data hierarchies to uncover insights like sales drivers by region, product, or customer segment.  
- **Custom Tooltips**: Displays detailed insights for specific visuals.  

---

## 🔍 Key Insights from the Dashboard  
1. **Overall Sales Performance**:  
   - Yearly trends in revenue and profit.  
   - Identification of top-performing and underperforming regions.  

2. **Product Analysis**:  
   - Best-selling products, profit margins, and product categories.  
   - Impact of product costs on retail pricing.  

3. **Customer Analysis**:  
   - Segmentation by region, buying behavior, and key demographics.  
   - Factors influencing home ownership among customers.  

4. **Key Influencers**:  
   - **Home Ownership** is strongly influenced by marital status (e.g., "S") and income levels.  
   - **Average Retail Price** increases proportionally with the sum of product costs.  

---

## 🚀 How to Use the Dashboard  
1. Open the Power BI file in **Power BI Desktop**.  
2. Navigate through different pages for specific insights (e.g., Product Details, Key Influencers).  
3. Use slicers and filters to analyze specific time periods, regions, or product categories.  
4. Hover over visuals to view additional information via tooltips.  

---

## 📈 Tools & Technologies Used  
- **Power BI Desktop**  
- **Power Query** for data cleaning and transformation.  
- **DAX** for calculated measures and KPIs, including:  
  - `SUM`, `SUMX`, `RANKX`, `CALCULATE`, `RELATED`, `ALL`, `ALLSELECTED`, `EXCEPT`.  
- **Power BI Service** for report sharing and collaboration (optional).  

---

## 🌟 Highlights  
- Comprehensive sales analysis with advanced features like Key Influencers and Decomposition Tree.  
- Extensive use of DAX for dynamic and custom calculations.  
- Interactive dashboards tailored for executives, product managers, and customer analysts.  
- Actionable insights to drive data-driven business decisions.  

---

