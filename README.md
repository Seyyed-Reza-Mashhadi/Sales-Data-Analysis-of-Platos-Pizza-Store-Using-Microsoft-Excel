### About Project: Plato's Pizza Sales Analysis   🍕🍕🍕

This project presents an interactive Excel-based dashboard analysis of Plato’s Pizza using a year’s worth of sales data. The objective is to identify performance patterns and operational insights that can support data-driven decisions.

Dataset Source: [Plato’s Pizza Sales Dataset on Kaggle](https://www.kaggle.com/datasets/shilongzhuang/pizza-sales)

### 🔍 Key Business Questions

- When is customer traffic at its peak?
Identify high-traffic days and hours based on average order volume to optimize staff scheduling, ingredient procurement, and operational efficiency during demand surges.

- What is the store’s pizza output during peak periods?
Quantify the number of pizzas sold during the busiest time slots to better forecast production needs and reduce delays, waste, or stockouts.

- Which pizzas perform best on specific weekdays?
Analyze day-by-day product preferences to uncover trends in customer ordering behavior, supporting menu planning, promotional targeting, and potential "pizza of the day" strategies.

- What is the total annual revenue, and how is it distributed across product categories?
Evaluate overall sales performance and segment revenue contributions by pizza category (e.g., Classic, Supreme, Veggie, Chicken) to identify core profit drivers and potential areas for repositioning or strategic emphasis.

- What does the revenue trend reveal over time, and are there identifiable sales spikes linked to seasons or events?
Examine fluctuations in daily revenue to detect stable growth patterns, high-performing timeframes, and potential opportunities for seasonal promotions or event-driven campaigns.


### ⚙️ Data Processing & Analysis Workflow

To prepare the dataset and build the interactive dashboard, the following steps were followed:
 - **Data Cleaning & ETL Operations (Power Query):**
    - Imported and cleaned raw sales data using Power Query
    - Standardized date and time formats, removed duplicates, and ensured data type consistency
    - Created a reference query to extract unique order dates 
    - Split time column into hour, minute, and second fields for granular time-based analysis

- **Data Modeling (Power Pivot):**
    - A data model was created in Power Pivot, establishing relationships between tables based on the order_id.
    - Useful DAX measures were developed, including total revenue, average pizzas sold per hour/day, quantity sold per category, etc. These measures enabled dynamic and scalable aggregation across different filters.

- **Interactive Dashboard Design:**
    - PivotTables and PivotCharts to show trends and breakdowns
    - Slicers for filtering by pizza category
    - A Timeline control for filtering by specific months and dates
    - KPI-style cards to highlight key metrics such as Total Revenue
    - Favorite Pizza of the Day section using a drop-down menu (using data validation option) and LOOKUP function to dynamically show the top-selling pizza for a selected weekday

- **User Experience Enhancements:**
    - Conditional formatting, simple and clean layout for clarity
    - Smart use of cell references and formulas to dynamically update visuals and outputs as required
    - Password protection was applied to the sheet to prevent accidental or unauthorized changes by end-users, ensuring data integrity and professional presentation.



### 📈📊 **Data-Driven Insights & Business Implications**
Two excel dashboards are created for addressing the key questions in this project (refer to [Excel File](https://github.com/Seyyed-Reza-Mashhadi/Sales-Data-Analysis-of-Platos-Pizza-Store-Using-Microsoft-Excel/blob/main/Pizza%20Sales%20Project.xlsx)):

**_Order Activity Dashboard_**
<img width="2004" height="855" alt="Image" src="https://github.com/user-attachments/assets/b3995b8c-97f4-43e7-b6ff-7dad5fc1b343" />

**_Revenue Dashboard_**
<img width="2004" height="850" alt="Image" src="https://github.com/user-attachments/assets/61d791a9-2223-409d-b6a9-0e0a492184f2" />

The analysis highlighted several key performance patterns that can inform decision-making at Plato’s Pizza:

- Total Revenue & Revenue Trends Over Time:
Total gross revenue (annual) is over $817,860. Although revenue is generally stable, occasional spikes hint at successful promotional activities or external events. Analyzing these spikes more closely can help replicate their success — for example, by aligning future campaigns with local events or repeating proven promotions. 

- Revenue by Product Category:
Classic pizzas generate the highest share of revenue, indicating strong customer preference. This suggests potential for targeted promotions (e.g., combo deals) centered on the Classic range. On the other hand, the lower-performing categories (like Chicken) may need reevaluation — through recipe innovation, pricing adjustments, or promotional boosts.

- Monthly Sales Trends:
Peak order volumes in specific months (such as July and November) indicate seasonal highs, which could be leveraged for future marketing campaigns or limited-time offers. Understanding the timing of these peaks helps with inventory planning, staff scheduling, and campaign timing.

- Weekly Order Patterns:
The highest average orders occur on weekends and late weekdays (especially Friday), implying these are high-traffic days. This insight can support labor optimization (e.g., more staff during peak shifts), as well as targeted marketing, such as weekend offers.

- Hourly Demand Fluctuations:
The busiest hours fall around lunchtime and early evening (12:00 to 14:00, and 17:00-19:00). These insights suggest optimal windows for flash deals, online delivery promotions, or queue management to improve service efficiency during peak hours.

- Product Popularity by Weekday:
The dashboard’s interactive component reveals the most frequently ordered pizza for each day of the week. This can be used to create “Pizza of the Day” specials, rotating discounts, or featured items to boost engagement and repeat business.


### 🎯 Strategic Recommendations


Based on the insights above, Plato’s Pizza can take the following actions to enhance operational efficiency and increase sales:

- Prioritize promotions for high-revenue categories like Classic pizzas, while experimenting with pricing or bundling for underperforming lines.

- Align staffing and inventory with peak hours, days, and seasonal demand to improve service and reduce operational friction.

- Leverage weekday product preferences to run targeted “Pizza of the Day” campaigns or limited-time offers that boost customer engagement.

- Capitalize on sales spikes by analyzing their drivers and replicating successful seasonal or event-based strategies.
