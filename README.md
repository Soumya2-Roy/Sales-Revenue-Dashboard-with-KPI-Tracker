# Sales Performance Dashboard & Analytics

## Project Overview

This project is an Advanced Excel Sales Performance Dashboard developed to transform transaction-level sales data into a clear and structured business analytics solution.

The dashboard brings together key performance indicators, sales and profit trends, category analysis, state-level performance, customer profitability, and sub-category analysis in a single management-oriented view.

The project helps understand where sales are coming from, which areas generate profit, which customers contribute the most, and where profitability requires attention.

The project uses Microsoft Excel to perform data preparation, KPI calculation, data aggregation, analysis, visualization, and dashboard development.

---

## Project Objectives

The main objectives of this project are:

- Analyze overall sales and profit performance.
- Track year-wise and month-wise sales trends.
- Measure key business KPIs.
- Compare sales and profitability across product categories.
- Analyze state-level sales and profit performance.
- Identify high-value and high-profit customers.
- Analyze sub-category performance.
- Identify strong and weak areas of business performance.
- Create a clear Excel dashboard for management reporting.
- Convert analytical findings into practical business recommendations.
- Present the analysis through charts, KPI cards, and summary views.
---


### Sales Revenue Dashboard with KPI Tracker

<img width="1858" height="778" alt="image" src="https://github.com/user-attachments/assets/7685c07c-1986-4288-8d71-d26acaabe54b" />

## Tools and Technologies

The project was developed using the following tools and techniques:

- Microsoft Excel
- Excel formulas
- Data aggregation
- KPI calculations
- Data cleaning and preparation
- Grouped analysis
- Time-based analysis
- Category analysis
- Sub-category analysis
- State-level analysis
- Customer-level analysis
- Excel charts
- Dashboard design
- Business data visualization

---

## Dataset Overview

The primary source for this project is the Sales Data sheet from the Excel workbook.

The dataset contains transaction-level sales information that can be analyzed across time, customers, geography, categories, sub-categories, products, sales, quantity, and profit.

| Metric | Value |
|---|---:|
| Sales Records | 9,993 |
| Unique Customers | 793 |
| Units Sold | 37,871 |
| Major Categories | 3 |
| Analysis Period | 2020–2023 |
| Total Sales | $2,296,919.70 |
| Total Profit | $286,409.85 |
| Profit Margin | 12.5% |
| Average Order Value | $229.91 |

---

## Main Data Fields

The analysis uses the following fields from the Sales Data sheet:

- Order Date
- Customer Name
- State
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Profit

These fields provide the foundation for calculating KPIs and performing business performance analysis.

---

## Key Performance Indicators

The dashboard contains the following major KPIs.

### Total Sales

**$2,296,919.70**

Total Sales represents the total value of sales generated across all transaction records.

Calculation:

```text
Total Sales = SUM(Sales)



Total Profit

$286,409.85

Total Profit represents the total profit generated from all sales transactions.

Calculation
Total Profit = SUM(Profit)

The overall profit margin is approximately 12.5%.

Profit Margin = (Total Profit / Total Sales) × 100
Total Orders

9,993

Total Orders represents the number of transaction records available in the Sales Data sheet.

Calculation
Total Orders = COUNT(Order Records)

The dataset contains 9,993 sales transaction records covering the period from 2020 to 2023.

Unique Customers

793

The dashboard contains sales transactions from 793 unique customers.

Calculation
Customers = COUNT(DISTINCT Customer Name)

This KPI helps measure the size of the customer base represented in the dataset.

Units Sold

37,871

Units Sold represents the total quantity of products purchased across all transactions.

Calculation
Units Sold = SUM(Quantity)
Average Order Value

$229.91

Average Order Value represents the average sales value generated per transaction.

Calculation
Average Order Value = Total Sales / Total Orders

The dashboard uses the total sales value and transaction count to determine the average order value.

Profit Margin

12.5%

Profit Margin measures the proportion of total sales represented by profit.

Calculation
Profit Margin = (Total Profit / Total Sales) × 100

Using the project data:

Profit Margin = ($286,409.85 / $2,296,919.70) × 100

The resulting value is approximately 12.5%.

Year-wise Sales Performance

The dashboard analyzes sales performance across the four years from 2020 to 2023.

Year	Sales
2020	$483,966.19
2021	$470,532.46
2022	$609,205.86
2023	$733,215.19
Year-wise Insight

Sales increased significantly from 2021 onwards.

The highest annual sales were recorded in 2023, with sales of $733,215.19.

The year-wise analysis helps identify changes in overall sales performance and provides a historical view of business growth.

Monthly Sales Analysis

Monthly analysis is used to understand changes in sales throughout the year and identify periods of higher and lower sales activity.

Month	Sales
January	$94,924.87
February	$59,751.26
March	$205,005.51
April	$137,480.79
May	$155,028.83
June	$152,718.72
July	$147,238.11
August	$159,043.99
September	$307,649.96
October	$200,323.03
November	$352,461.09
December	$325,293.54
Monthly Insight

November recorded the highest monthly sales at approximately $352,461.09.

December recorded approximately $325,293.54, while September recorded approximately $307,649.96.

February recorded the lowest monthly sales at approximately $59,751.26.

The monthly analysis provides a useful view of seasonal changes in sales activity.

Category Performance

The dashboard compares sales and profitability across the three major product categories.

Category	Sales	Profit
Technology	$836,154.10	$145,455.66
Furniture	$741,718.61	$18,463.31
Office Supplies	$719,046.99	$122,490.88
Category Insight

Technology generated the highest sales at $836,154.10 and also generated the highest profit at $145,455.66.

Office Supplies generated $719,046.99 in sales and $122,490.88 in profit.

Furniture generated $741,718.61 in sales, but its profit contribution was considerably lower at $18,463.31.

This demonstrates that sales volume and profitability can differ significantly across categories.

State-level Performance

The dashboard analyzes sales and profitability across different states.

The major state-level results include:

State	Sales	Profit
New Delhi	$502,576.82	$52,783.24
Bihar	$457,687.68	$76,381.60
Himachal Pradesh	$205,985.75	-$18,959.29
Odisha	$162,346.81	$40,433.90
Kerala	$137,084.81	-$19,703.86
Meghalaya	$116,157.84	$32,042.68
Goa	$91,361.20	-$13,447.87
Madhya Pradesh	$84,217.28	$13,041.31
Rajasthan	$77,872.75	$24,563.35
Jharkhand	$71,723.80	$23,535.72
State Performance Insight

New Delhi recorded the highest sales among the states shown, with $502,576.82.

Bihar generated the highest profit among the states shown, with $76,381.60.

Some states generated substantial sales while recording negative profit. For example:

Himachal Pradesh: -$18,959.29
Kerala: -$19,703.86
Goa: -$13,447.87

This demonstrates the importance of evaluating both sales and profit when analyzing geographical performance.

Customer Profitability Analysis

The dashboard includes a Top 5 Customers by Profit analysis.

Customer	Profit
Tamara Chand	$8,981.32
Raymond Buch	$6,976.09
Sanjit Chand	$5,757.42
Hunter Lopez	$5,622.43
Adrian Barton	$5,444.81
Customer Insight

Tamara Chand generated the highest profit among the customers shown in the Top 5 analysis, with a profit contribution of $8,981.32.

Customer-level analysis helps identify customers who contribute strongly to profitability.

Sub-Category Analysis

The dashboard also analyzes sales and profitability at the sub-category level.

Sub-Category	Sales	Profit
Phones	$330,007.10	$44,516.25
Chairs	$328,167.76	$26,602.21
Storage	$223,843.59	$21,279.05
Tables	$206,965.68	-$17,725.59
Binders	$203,412.77	$30,221.64
Machines	$189,238.68	$3,384.73
Accessories	$167,380.31	$41,936.78
Copiers	$149,528.01	$55,617.90
Bookcases	$114,880.05	-$3,472.56
Appliances	$107,532.14	$18,138.07
Furnishings	$91,705.12	$13,059.25
Paper	$78,479.24	$34,053.34
Supplies	$46,673.52	-$1,188.99
Art	$27,118.80	$6,527.96
Envelopes	$16,476.38	$6,964.10
Sub-Category Insight

Phones generated the highest sales among the sub-categories shown, with $330,007.10.

Some sub-categories generated significant sales but recorded negative profit.

For example, Tables generated $206,965.68 in sales but recorded -$17,725.59 in profit.

This highlights the importance of analyzing profitability together with sales.

Dashboard Components

The Excel dashboard combines several analytical views into a single management-oriented interface.

KPI Cards

The dashboard displays:

Total Sales
Total Profit
Total Orders
Customers
Units Sold
Average Order Value
Profit Margin
Sales Trend Analysis

Sales trends provide a time-based view of business performance and help identify changes across years and months.

Category Analysis

Category-level analysis compares:

Technology
Furniture
Office Supplies
State Analysis

State-level analysis identifies geographical areas with high sales and profit as well as areas requiring further profitability investigation.

Customer Analysis

The Top 5 Customers by Profit section identifies customers contributing strongly to overall profitability.

Sub-Category Analysis

Sub-category analysis provides a detailed view of product-level sales and profit performance.

Dashboard Methodology

The project follows a structured analytical workflow:

Sales Data
    ↓
Data Preparation
    ↓
Data Validation
    ↓
KPI Calculation
    ↓
Year & Month Analysis
    ↓
Category Analysis
    ↓
State Analysis
    ↓
Customer Analysis
    ↓
Sub-Category Analysis
    ↓
Charts & Visualizations
    ↓
Excel Dashboard
    ↓
Business Insights
Data Preparation

The Sales Data sheet was used as the primary analytical dataset.

The important fields used for analysis include:

Order Date
Customer Name
State
Category
Sub-Category
Product Name
Sales
Quantity
Profit

The dataset was organized to support:

Time-based analysis
Category analysis
State-level analysis
Customer analysis
Sub-category analysis
KPI calculation
Dashboard visualization
Key Business Insights

The analysis generated the following major observations:

2023 recorded the highest annual sales, reaching $733,215.19.
Technology generated the highest category sales, with $836,154.10.
Technology also generated the highest category profit at $145,455.66.
New Delhi recorded the highest state-level sales, with $502,576.82.
Bihar generated the highest state-level profit among the states shown, at $76,381.60.
November recorded the highest monthly sales, with approximately $352,461.09.
Phones generated the highest sub-category sales, with $330,007.10.
Tamara Chand generated the highest customer profit among the customers shown, at $8,981.32.
Some states and sub-categories generated substantial sales but negative profit.
The overall dataset generated approximately $286,409.85 profit from $2.30 million in sales.
Business Recommendations

Based on the dashboard analysis, the following areas can be considered for further business attention.

1. Monitor High-Sales Categories

Technology generates the highest sales and profit in the dataset. Its performance can be monitored to understand which products and sub-categories are contributing to this result.

2. Review Low-Profit Product Areas

Sub-categories such as Tables, Bookcases, and Supplies recorded negative profit.

These areas can be examined further based on:

Pricing
Discounting
Product costs
Product mix
Order-level profitability
3. Investigate Negative-Profit States

States such as Kerala, Himachal Pradesh, and Goa recorded negative profit despite generating sales.

Further analysis can investigate the product mix and transaction-level profitability within these states.

4. Analyze High-Value Customers

Customers generating strong profit can be examined to understand their purchasing patterns, product preferences, and order frequency.

5. Use Seasonal Sales Patterns

The stronger sales observed during the later months of the year can be considered when planning future inventory, promotions, and sales activities.

Excel Dashboard Design

The dashboard is designed as a management reporting interface.

The main dashboard contains:

KPI CARDS
│
├── Total Sales
├── Total Profit
├── Total Orders
├── Customers
├── Units Sold
├── Average Order Value
└── Profit Margin

ANALYTICAL VISUALS
│
├── Monthly Sales Trend
├── Profit by Year & Category
├── Sales by Category
├── Top 5 Customers by Profit
└── Top States by Sales

This structure allows users to move from high-level KPIs to detailed business analysis.

Project Deliverables

The project includes the following deliverables:

Excel Sales Performance Dashboard
KPI calculations
Sales trend analysis
Profit analysis
Category analysis
State-level analysis
Customer profitability analysis
Sub-category analysis
Business insights
Business recommendations
Project presentation
Project report
GitHub project documentation
Learning Outcomes

Through this project, the following skills were developed:

Advanced Excel data analysis
Data cleaning and preparation
KPI development
Business performance analysis
Excel formula implementation
Data aggregation
Time-series analysis
Category analysis
Geographical analysis
Customer profitability analysis
Dashboard development
Data visualization
Business insight generation
Management reporting
Future Scope

The dashboard can be further enhanced by adding:

Interactive slicers and filters
Automated data refresh
Product-level drill-down
Customer segmentation
Customer lifetime value analysis
Profit margin by product
Discount analysis
Sales forecasting
Profit forecasting
Year-over-year growth analysis
Regional drill-down analysis
Power BI integration
Automated dashboard reporting
Project Structure
Sales-Performance-Dashboard/
│
├── README.md
│
├── Sales_Dashboard_KPIs_Final.xlsx
│
├── Screenshots/
│   └── dashboard.png
│
├── Presentation/
│   └── Sales_Dashboard_Project_Presentation.pptx
│
└── Report/
    └── Sales_Dashboard_Project_Report.docx
Data Source

The primary data source for the project is the Sales Data sheet in the supplied Excel workbook.

The analysis and dashboard calculations are based on the transaction-level sales records contained within this dataset.

KPI Definitions
KPI	Definition
Total Sales	Sum of all Sales values
Total Profit	Sum of all Profit values
Total Orders	Number of transaction records
Customers	Number of unique customers
Units Sold	Sum of Quantity
Average Order Value	Total Sales divided by Total Orders
Profit Margin	Total Profit divided by Total Sales
Category Sales	Sales aggregated by Category
State Sales	Sales aggregated by State
Customer Profit	Profit aggregated by Customer
Sub-Category Sales	Sales aggregated by Sub-Category
Limitations

The current analysis is based on the available transaction-level dataset and the fields contained within the supplied workbook.

The dashboard does not currently include detailed information such as:

Marketing expenditure
Inventory levels
Operating expenses
Customer acquisition cost
Product cost breakdown
Delivery performance
Employee costs

Therefore, the analysis focuses primarily on:

Sales
Profit
Quantity
Customers
Categories
Sub-categories
States
Time-based performance
Conclusion

The Sales Performance Dashboard & Analytics project demonstrates how Microsoft Excel can be used to transform transaction-level sales data into a structured business intelligence solution.

The dashboard provides a consolidated view of sales, profitability, customers, products, categories, states, and time-based performance.

The analysis shows total sales of $2,296,919.70, total profit of $286,409.85, 9,993 transaction records, 793 unique customers, and 37,871 units sold.

The dashboard also identifies important patterns such as the strong performance of Technology, the high sales contribution from New Delhi, the highest annual sales in 2023, and the importance of reviewing areas where high sales do not translate into positive profit.

Overall, the project demonstrates practical skills in Excel analytics, KPI development, data visualization, dashboard design, and business intelligence reporting.

Author

Soumya Roy

Project: Sales Performance Dashboard & Analytics

Tool: Microsoft Excel

Analysis Period: 2020–2023


