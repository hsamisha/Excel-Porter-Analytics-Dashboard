# Porter Analytics - Excel Dashboard

## Project Overview

The Porter Analytics project is an Excel-based data analysis and dashboard project focused on analyzing food delivery order data and understanding order patterns, delivery performance, food categories, pricing, order quantities, and delivery operations.

The project uses Microsoft Excel to clean, transform, analyze, and visualize food delivery data through Excel calculations, pivot tables, charts, and dashboard reporting.

The analysis provides insights into delivery duration, order activity, food categories, item quantities, order values, delivery partner availability, and outstanding orders.

## Objective

The main objectives of this project are to:

- Analyze food delivery order data.
- Understand delivery time patterns.
- Analyze order activity across different days and times.
- Examine food and restaurant categories.
- Analyze order quantities and distinct items.
- Understand order subtotal and pricing patterns.
- Analyze delivery partner availability and workload.
- Examine outstanding orders.
- Identify operational patterns affecting delivery performance.
- Analyze order activity by date and time.
- Present important operational metrics through an Excel dashboard.
- Generate meaningful insights from the available data.

## Dataset Description

The project uses a food delivery order dataset containing information about orders, stores, food categories, order timing, item quantities, pricing, and delivery-partner activity.

The main dataset contains approximately 197,429 order records and includes information such as:

- Market
- Order creation time
- Actual delivery time
- Store
- Store category
- Order protocol
- Number of items
- Order subtotal
- Distinct items
- Minimum item price
- Maximum item price
- Delivery partners on shift
- Busy delivery partners
- Outstanding orders

### Important Columns

| Column | Description |
|---|---|
| `market_id` | Identifier for the market |
| `created_at` | Date and time when the order was created |
| `actual_delivery_time` | Date and time when the order was delivered |
| `store_id` | Unique identifier of the store |
| `store_primary_category` | Primary category of the store |
| `order_protocol` | Order protocol used |
| `total_items` | Total number of items in the order |
| `subtotal` | Order subtotal |
| `num_distinct_items` | Number of distinct items in the order |
| `min_item_price` | Minimum item price |
| `max_item_price` | Maximum item price |
| `total_onshift_partners` | Number of delivery partners on shift |
| `total_busy_partners` | Number of busy delivery partners |
| `total_outstanding_orders` | Number of outstanding orders |

Additional calculated fields were created for analysis, including:

- Date
- Time
- Day Name
- Month Name
- Quarter
- Duration Minutes
- Rounded Duration
- Quantity Size

## Tools & Technologies Used

- Microsoft Excel
- Excel Tables
- Excel Formulas
- Pivot Tables
- Pivot Charts
- Data Cleaning
- Data Transformation
- Data Analysis
- Data Visualization
- Dashboard Design

## Approach / Methodology

The project was completed through the following stages.

### 1. Data Collection

The food delivery dataset was loaded into Microsoft Excel and organized in the `RAW` worksheet.

### 2. Data Understanding

The dataset was examined to understand:

- Order information
- Store information
- Food categories
- Order timing
- Item quantities
- Pricing
- Delivery duration
- Delivery partner information
- Outstanding orders

### 3. Data Cleaning

The raw data was reviewed and prepared for analysis by checking:

- Missing values
- Date and time fields
- Numerical fields
- Categorical fields
- Order-related variables
- Delivery-related variables

### 4. Data Transformation

Additional fields were created to support the analysis:

- Date
- Time
- Day Name
- Month Name
- Quarter
- Duration Minutes
- Round
- Round2
- Quantity Size

These fields helped perform time-based and operational analysis.

### 5. Exploratory Data Analysis

The dataset was analyzed to understand:

- Delivery duration
- Order volume
- Food categories
- Order quantities
- Subtotals
- Item prices
- Delivery partner activity
- Outstanding orders
- Daily order patterns
- Time-based order patterns

### 6. Pivot Table Analysis

Pivot tables and Excel calculations were used to summarize important metrics, including:

- Average delivery duration by day
- Average delivery duration by hour
- Average delivery duration by market
- Average order quantity
- Food category subtotal
- Subtotal by date
- Subtotal by time
- Minimum item price
- Maximum item price

### 7. Dashboard Development

The analyzed data was used to create an Excel dashboard containing KPIs, charts, and visual summaries.
<img width="1433" height="667" alt="image" src="https://github.com/user-attachments/assets/7020f6d0-98f3-4b07-a7bd-a40a44a8dd63" />
The dashboard provides a consolidated view of food delivery performance and operational patterns.

## Analysis & Key Findings

### Delivery Duration Analysis

The overall average delivery duration in the analyzed calculations is approximately **34.45 minutes**.

Delivery duration was analyzed across different days, hours, markets, and order characteristics.

### Delivery Duration by Day

The analysis shows that average delivery duration varies across the days of the week.

| Day | Average Duration |
|---|---:|
| Sunday | 33.57 minutes |
| Monday | 29.56 minutes |
| Tuesday | 22.17 minutes |
| Wednesday | 33.67 minutes |
| Thursday | 38.36 minutes |
| Friday | 34.29 minutes |
| Saturday | 42.50 minutes |

Saturday has the highest average delivery duration among the analyzed days, while Tuesday has the lowest.

### Delivery Duration by Time

Delivery duration also varies by order hour.

The analysis includes delivery-duration comparisons across different hours, allowing periods with longer or shorter delivery times to be identified.

### Order Quantity Analysis

The average number of items per order in the analyzed calculations is approximately **3.8 items**.

Orders were grouped into quantity categories to understand differences in order size and item volume.

### Food Category Analysis

The project analyzes order subtotals across multiple food categories.

The dataset includes categories such as:

- American
- Mexican
- Chinese
- Indian
- Italian
- Japanese
- Greek
- Dessert
- Middle Eastern
- Seafood
- Sushi
- Vegetarian
- Vegan
- Pizza
- Burger
- Sandwich
- Thai
- Korean
- Mediterranean
- Other

The category analysis helps compare order value and activity across different food categories.

### Subtotal Analysis

Order subtotal was analyzed across food categories, dates, and times.

This provides a way to understand differences in order-value activity across categories and time periods.

### Pricing Analysis

The dataset contains minimum and maximum item-price fields.

These were analyzed to understand pricing differences across markets and order characteristics.

### Delivery Partner Analysis

The project includes operational variables related to delivery partners:

- Total on-shift partners
- Total busy partners
- Total outstanding orders

These metrics can be used to understand delivery-partner workload and operational pressure.

## Analysis & Key Insights

Based on the calculations and analysis performed in the Excel workbook, the following key insights were identified:

- The dataset contains approximately **197,429 order records**.
- The overall average delivery duration is approximately **34.45 minutes**.
- Delivery duration varies across different days of the week.
- **Saturday** has the highest average delivery duration among the analyzed days at approximately **42.50 minutes**.
- **Tuesday** has the lowest average delivery duration among the analyzed days at approximately **22.17 minutes**.
- The average number of items per order is approximately **3.8 items**.
- The dataset contains a wide range of food categories, allowing category-level analysis of order activity and subtotal.
- Order subtotal varies across food categories, dates, and times.
- Delivery duration varies across different order hours.
- Minimum and maximum item prices provide additional information for market-level pricing analysis.
- The number of busy delivery partners and outstanding orders can be used to understand operational workload.
- The calculated date, time, day, month, quarter, duration, and quantity fields support deeper operational analysis.

These findings are based on the calculations and data available in the Excel project.

## Dashboard Overview

The Excel project includes a dashboard for presenting the major Porter Analytics findings.

The dashboard focuses on:

- Total Orders
- Average Delivery Duration
- Average Items per Order
- Order Subtotal
- Delivery Duration by Day
- Delivery Duration by Time
- Food Category Analysis
- Order Quantity Analysis
- Pricing Analysis
- Delivery Partner Activity
- Outstanding Orders

The dashboard provides a summarized view of food delivery operations and helps users understand order and delivery patterns.

## Key Performance Indicators

| KPI | Description |
|---|---|
| Total Orders | Total number of orders analyzed |
| Average Delivery Duration | Average time taken to deliver an order |
| Average Items per Order | Average number of items in an order |
| Total Subtotal | Total order value represented in the analysis |
| On-Shift Partners | Number of delivery partners on shift |
| Busy Partners | Number of delivery partners currently busy |
| Outstanding Orders | Number of outstanding orders |

## Recommendations

Based on the analysis performed, the following recommendations can be considered:

- Monitor delivery duration across different days and time periods.
- Analyze periods with longer delivery times to identify possible operational bottlenecks.
- Align delivery-partner availability with order demand.
- Monitor outstanding orders to identify workload pressure.
- Analyze busy-partner levels together with outstanding orders.
- Monitor food-category performance and order-value patterns.
- Analyze order quantity patterns for better operational planning.
- Monitor pricing differences across markets and food categories.
- Use time-based order analysis to improve staffing and delivery allocation.
- Regularly monitor delivery performance to identify changes in operational efficiency.

## Conclusion

The Porter Analytics Excel project demonstrates how Microsoft Excel can be used to analyze food delivery operations and generate meaningful business insights.

The project covers delivery duration, order quantity, food categories, pricing, order timing, order subtotals, delivery-partner availability, and outstanding orders.

Using Excel data cleaning, calculated fields, pivot tables, analysis, and dashboard visualization, the project transforms raw food delivery data into understandable operational insights.

Overall, the project demonstrates practical skills in Excel-based data cleaning, data transformation, exploratory analysis, pivot table analysis, KPI development, data visualization, and dashboard design.


├── README.md
└── Dashboard/
    └── Porter Analytics Dashboard
