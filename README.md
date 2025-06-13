# Interactive Ecommerce Analytics Dashboard Using Power BI

## Project Overview
This project implements an interactive, insight-driven ecommerce dashboard that enables real-time tracking of sales performance, customer behaviour, and profitability across multiple dimensions such as time, region, product category, and payment mode. The dashboard facilitates data-driven decision-making through dynamic visuals and user-controlled filters.

## Tools & Technologies Used
- **Data Visualization**: Power BI Desktop
- **Data Preparation**: Power Query
- **DAX (Data Analysis Expressions)**: For custom KPIs and calculated measures
- **Data Source**: Structured CSV/Excel files with sales and customer transaction records

## Dashboard Features & Functionality

### 1. Interactive Filtering & User Input Controls
- Slicer-based filters for Quarter, State, and Customer
- Dynamic KPI adjustments based on user selections
- Enables stakeholders to focus on specific time frames or regional performance

### 2. Key Performance Indicators (KPIs)
- Total Sales Amount
- Total Quantity Sold
- Total Profit
- Average Order Value (AOV)

*Note: All KPIs are dynamic and update automatically based on filter selections (e.g., state, quarter, customer), allowing real-time drilldown and segmentation.*

### 3. Regional Sales Analysis
- Bar chart showing sales performance by state
- Helps identify high-performing regions and regional growth opportunities

### 4. Time-Based Profit Trend
- Monthly profit distribution visualised across selected quarter
- Reveals sales peaks, seasonal trends, and underperforming months

### 5. Customer-Level Performance Analysis
- Dynamic bar chart displays sales amount by individual customers
- Enables identification of top spenders and loyal buyers
- Supports segmentation and targeted marketing strategies

### 6. Payment Method Distribution
- Donut chart categorises quantity sold by payment mode (e.g., Debit Card, UPI, COD, etc.)
- Offers insights into customer transaction behaviour and preferred payment channels

### 7. Product Performance Insights
- **Category-Level**: Quantity sold across Clothing, Electronics, Furniture, etc.
- **Sub-Category Profitability**: Highlights profit contribution by product groups like Accessories, Bookcases, T-shirts, etc.
- Aids in product strategy, pricing decisions, and inventory planning

## Business Insights Derived
- Sales, profit, and AOV vary significantly across quarters and customer segments, emphasising the importance of seasonal planning and targeted marketing.
- Clothing and Accessories categories consistently contribute higher volume and profit, indicating strong consumer preference.
- Digital payments (e.g., Debit Card and UPI) are dominant, supporting investment in cashless infrastructure.
- Gujarat (in selected view) emerged as a high-performing state, valuable for regional targeting and sales campaigns.
- Certain months like January show profit spikes, suggesting promotional or seasonal campaign effects.

## Challenges Faced
- Managing data variability caused by filter-driven visual changes while maintaining accurate metric calculations.
- Designing a layout that supports multiple responsive visuals without overwhelming the user.
- Constructing DAX measures for AOV and Profit to remain responsive and error-free across different filter combinations.

## Future Improvements
1. Integrate customer demographics for cohort analysis
2. Add YoY (Year-over-Year) and MoM (Month-over-Month) comparisons for revenue and profit
3. Include order-level drill-through pages with product-wise margins
4. Connect to a real-time data source or API for automatic refresh
5. Develop alerting logic using Power BI Service for underperforming KPIs

## Conclusion
The Ecommerce Sales Dashboard is a robust business intelligence solution that delivers real-time, filter-driven insights through dynamic KPIs and interactive visuals. By combining effective data modelling with intuitive design, it enables business users to monitor regional sales trends, identify top customers, evaluate product performance, and optimise operational strategies. The project showcases strong data visualisation, DAX modelling, and dashboard development skills using Power BI — essential for any data analyst or business intelligence role. 