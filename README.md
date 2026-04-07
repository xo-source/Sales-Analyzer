Note: This project focuses on handling real-world messy and skewed data rather than ideal datasets.

# Sales-Analyzer

This project analyzes an Adidas sales dataset to explore sales performance across different cities, 
products, and regions. The goal is to clean the data, identify trends, and detect potential outliers.

### Tasks Performed
Cleaned the dataset (checked for missing values and duplicates)
Aggregated total sales by city, product, and region
Visualized sales trends using bar charts
Detected outliers using IQR on log-transformed data to handle skewness

### Key Insights
Sales are highly right-skewed, with a few cities contributing significantly more than others
After applying a log transformation, no extreme statistical outliers were detected
Certain cities consistently generate higher total sales compared to others

### Visualizations
City vs Total Sales
City vs Product Count

### Techniques Used
Data cleaning with pandas
Grouping and aggregation (groupby)
Data visualization with matplotlib
Log transformation for skewed data
Outlier detection using IQR
