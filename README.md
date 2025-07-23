<h3 align="center">🍕🍕🍕   Plato's Pizza Sales Analysis   🍕🍕🍕</h3> <br>

### About Project 
This project presents interactive Excel-based dashboard analysis of Plato’s Pizza using a year’s worth of sales data.

🔗 Dataset Source: [Plato’s Pizza Sales Dataset on Kaggle](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)

### 🔍 Key Business Objectives
This analysis aims to optimize Plato's Pizza operations through 5 key objectives:
- Identify peak traffic days/hours to optimize staffing and inventory
- Quantify pizzas sold during peak periods for production forecasting
- Determine top-performing pizzas by weekday for menu strategy
- Analyze revenue distribution across pizza categories 
- Track seasonal revenue trends for promotional opportunities

### ⚙️ Data Processing & Analysis Workflow
- **Data Cleaning & ETL (Power Query)**
    - Imported and cleaned raw sales data
    - Removed duplicates, standardized date and time formats, and ensured data type consistency
    - Created a reference query to extract unique dates 
    - Split date column (year/month/day) and time column (hour/minute/second)

- **Data Modeling (Power Pivot)**
    - Established relationships in the model based on the order_id column.
    - Enabled Dynamic aggregation across columns 
    - Created DAX measures such as total revenue, average pizza orders per hour/day, etc. 

- **Interactive Dashboard Design**
    - Created PivotTables / PivotCharts 
    - Implemented filtering controls including slicers and timelines
    - Designed KPI cards (e.g., Total Revenue)
    - Built "Favorite Pizza of the Day" feature using data validation and LOOKUP function

- **UX Optimization & Dashboard Protection**
    - Enhanced visual clarity through conditional formatting and simple plots
    - Enabled dynamic functionality using cell references/formulas
    - Implemented password protection to prevent unauthorized edits by end-users

### 📈📊 **Key Data-Driven Insights & Business Implications**
Two excel dashboards are created for this project (refer to [Excel File](https://github.com/Seyyed-Reza-Mashhadi/Sales-Data-Analysis-of-Platos-Pizza-Store-Using-Microsoft-Excel/blob/main/Pizza%20Sales%20Project.xlsx)):

_Order Activity Dashboard_
<img width="2004" height="855" alt="Image" src="https://github.com/user-attachments/assets/b3995b8c-97f4-43e7-b6ff-7dad5fc1b343" />

_Revenue Dashboard_
<img width="2004" height="850" alt="Image" src="https://github.com/user-attachments/assets/61d791a9-2223-409d-b6a9-0e0a492184f2" />

The analysis highlighted several key performance patterns that can inform decision-making at Plato’s Pizza:

- Total Revenue & Revenue Trends Over Time:
Total gross revenue (annual) is over $817,860. Although revenue is generally stable, occasional spikes hint at successful promotional activities or external events. Analyzing these spikes more closely can help replicate their success — for example, by aligning future campaigns with local events or repeating proven promotions. 

- Revenue by Product Category:
Classic pizzas generate the highest share of revenue, indicating strong customer preference. This suggests potential for targeted promotions (e.g., combo deals) centered on the Classic range. On the other hand, the lower-performing categories may need re-evaluation — through recipe innovation, pricing adjustments, or promotional boosts.

- Monthly Sales Trends:
Peak order volumes in specific months (such as July and November) indicate seasonal highs, which could be leveraged for future marketing campaigns or limited-time offers. Understanding the timing of these peaks helps with inventory planning, staff scheduling, and campaign timing.

- Weekly Order Patterns:
The highest average orders occur on weekends and late weekdays (especially Friday), implying these are high-traffic days. This insight can support labor optimization (e.g., more staff during peak shifts), as well as targeted marketing, such as weekend offers.

- Hourly Demand Fluctuations:
The busiest hours fall around lunchtime and early evening (12:00 to 14:00, and 17:00-19:00). These insights suggest optimal windows for flash deals, online delivery promotions, or queue management to improve service efficiency during peak hours.

- Product Popularity by Weekday:
The dashboard’s interactive component reveals the most frequently ordered pizza for each day of the week. This can be used to create “Pizza of the Day” specials, discounts, or featured items to boost engagement and repeat business.


### 🎯 Strategic Recommendations

- 🚀 Bundle Classic pizzas with lower-performing categories 
- 📅 Launch "Pizza of the Day" based on weekday preferences to boost customer engagement
- 👨‍🍳 Align staff schedules with Friday/weekend rushes to improve service and reduce operational friction 
- 🎉 Replicate July/November spikes through seasonal promotions
