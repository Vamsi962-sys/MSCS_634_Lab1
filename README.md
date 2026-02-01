# MSCS 634 – Lab 1: Data Visualization, Preprocessing and Statistical Analysis

## Purpose of the Lab

The purpose of this lab was to gain hands-on experience with data visualization, data preprocessing, and basic statistical analysis using Python in JupyterLab. Using a sales dataset, I explored the data, cleaned and transformed it, and prepared it for deeper analysis. This lab helped me understand how raw datasets can be converted into meaningful, structured data suitable for machine learning and analytics.

## Key Insights from Visualizations and Statistical Measures

From the sales distribution histogram, I observed that most transactions fall within lower sales values, indicating that smaller purchases are more common than large orders. The bar chart of order status showed that the majority of orders were marked as *Shipped*, suggesting strong order fulfillment performance, while fewer orders were cancelled or disputed.

Statistical analysis provided additional understanding of the dataset. Measures of central tendency such as mean and median highlighted the typical sales values, while dispersion measures like standard deviation and interquartile range showed that sales amounts vary widely. The correlation matrix revealed relationships between numerical variables such as sales, quantity ordered, and price, helping identify which features move together.

## Challenges Faced and Decisions Made

One of the main challenges was handling file loading errors and encoding issues when importing the CSV file, which was resolved by specifying the correct encoding format. Another challenge was managing missing values and outliers, which required applying mean replacement for numerical columns and IQR-based filtering for extreme values. I also reduced the dataset size using sampling and removed less relevant columns to improve performance. Min-Max scaling and discretization were applied to normalize the data and categorize sales values for easier interpretation.

Overall, this lab strengthened my understanding of data preprocessing workflows and demonstrated how visualization and statistics guide data-driven decisions.
