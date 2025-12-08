# pizza_sales_dashboard
An end-to-end data analytics project transforming raw pizza sales data into actionable business insights through SQL querying and Excel visualization.

Business Questions Answered
This dashboard provides comprehensive analysis of pizza sales performance, helping stakeholders understand revenue trends, customer preferences, and product performance to drive data-informed business decisions.
Key Performance Indicators
Total Revenue: Overall sales performance tracking
Average Order Value: Customer spending patterns
Total Pizzas Sold: Volume metrics
Total Orders: Transaction frequency analysis
Average Pizzas per Order: Order composition insights

Analytical Insights

Daily ordering patterns and trends
Peak hours for order activity
Sales distribution across pizza categories
Customer preferences by pizza size
Category performance comparison
Top 5 bestselling pizzas
Bottom 5 underperforming pizzas

Tools & Technologies

SQL: Data extraction and querying
Microsoft Excel: Data cleaning, transformation, and visualization
Data Analysis: Statistical analysis and trend identification

Project Structure
pizza-sales-dashboard/
│
├── data/
│   └── pizza_sales_data.csv          # Raw dataset
│
├── sql/
│   └── analysis_queries.sql          # SQL queries used
│
├── dashboard/
│   └── pizza_sales_dashboard.xlsx    # Final Excel dashboard
│
├── screenshots/
│   ├── dashboard_overview.png
│   ├── daily_trends.png
│   └── top_sellers.png
│
└── README.md

Data Cleaning & Preparation
Data Normalization

Pizza Size Standardization: Converted coded values (S, M, L, XL, XXL) to descriptive labels (Small, Medium, Large, Extra Large, Extra Extra Large) using Excel's Find & Replace function
Improved Readability: Enhanced professional presentation and user understanding

Temporal Feature Engineering

Day Extraction: Utilized Excel's TEXT function to extract day of the week from date fields
Trend Analysis: Enabled daily pattern recognition without manual categorization
Time-based Insights: Facilitated hourly and daily trend analysis

Data Quality Assurance

Validated data consistency across all fields
Checked for and handled missing values
Ensured logical relationships between metrics

Dashboard Components
1. Daily Trend Analysis (Bar Chart)

Visualizes order volume patterns across different days of the week
Identifies peak business days for staffing and inventory planning

2. Hourly Trend Analysis (Line Chart)

Maps order activity throughout the day
Pinpoints peak hours for operational optimization

3. Sales by Category (Pie Chart)

Shows distribution across pizza categories (Classic, Veggie, Supreme, Chicken)
Reveals category popularity and contribution to total sales

4. Sales by Size (Pie Chart)

Analyzes customer preferences across pizza sizes
Informs inventory and pricing strategies

5. Category Performance (Funnel Chart)

Compares total pizzas sold by category
Enables performance benchmarking across product lines

6. Top 5 Bestsellers (Bar Chart)

Highlights star products driving revenue
Guides promotional and inventory decisions

7. Bottom 5 Performers (Bar Chart)

Identifies underperforming products
Supports menu optimization and product development

Key Insights

Peak Days: Friday and Saturday generate 35% of weekly orders
Rush Hours: 12-1 PM and 6-7 PM are peak ordering times
Popular Categories: Classic pizzas account for 40% of sales
Size Preference: Large pizzas are the most ordered size at 45%
Top Seller: The Classic Deluxe Pizza leads with 2,453 units sold

Skills Demonstrated

Data Cleaning: Normalization, standardization, and quality assurance
SQL: Complex queries for data extraction and aggregation
Excel Functions: TEXT, VLOOKUP, PivotTables, conditional formatting
Data Visualization: Chart selection, color theory, dashboard design
Business Analysis: Translating data into actionable business insights
Storytelling: Presenting complex data in an accessible format
