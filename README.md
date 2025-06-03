# data-analyst-task2-superstore-visualization
# Task 2: Data Visualization and Storytelling

**Objective**: Create visualizations to tell a story using the Superstore sales dataset.

**Dataset Used**: Sample_Superstore_Task2.csv (9994 rows, 21 columns initially)

**Tools**: Power BI

**Data Cleaning Steps (Power Query Editor)**:
- Removed unnecessary columns (`Row ID`, `Ship Date`, etc.).
- Retained specified columns: `Order ID`, `Customer ID`, `Customer Name`, `Product Name`, `Ship Mode`, `Country`.
- Confirmed no missing values or duplicates.
- Standardized `Order Date`, added `Year` and `Month`.
- Cleaned text columns (`Customer Name`, `Product Name`, etc.).
- Verified data types.
- Kept negative profits for realistic analysis.

**Visualizations**:
- **Sales by Region (Bar Chart)**: West leads; `Ship Mode` slicer added.
- **Profit by Category (Pie Chart)**: Technology drives highest profit.
- **Sales Trend Over Time (Line Chart)**: Peaks in November/December.
- **Profit Margin by Segment (Funnel Chart)**: Corporate segment leads profitability.
- **Sales by Ship Mode and Region (Waterfall Chart)**: Standard Class in West drives sales.
- **Top 5 Sub-Categories by Sales (Bar Chart)**: Chairs and Phones dominate; tooltips show `Product Name`, `Customer Name`.
- **Summary Slide**: Consolidated insights with miniature visuals for strategic decisions.

**Files Included**:
- `Sample_Superstore_Task2.csv`: Original dataset
- `Superstore_Visual_Report.pdf`: Visual report
- Screenshots: `Sales_by_Region.png`, `Profit_by_Category.png`, `Sales_Trend_Over_Time.png`, `Profit_Margin_by_Segment_Funnel.png`, `Sales_by_Ship_Mode_and_Region_Waterfall.png`, `Top_5_Sub_Categories.png`, `Summary_Slide.png`
- `Superstore_Dashboard.pbix`: Power BI file
- `README.md`: This summary
