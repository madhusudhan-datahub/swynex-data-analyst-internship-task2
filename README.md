**SWYNEX Data Analyst Internship — Task 2**

**Exploratory Data Analysis**

📌   **Project Overview**

This project was completed as part of my Data Analyst Internship with SWYNEX Technologies.

The objective of this task was to perform Exploratory Data Analysis (EDA) on the cleaned Online Retail dataset and identify meaningful trends, patterns, and potential anomalies.

📊 **Dataset**

Dataset: UCI Online Retail Dataset

The cleaned dataset from Task 1 was used for this analysis.

**Dataset size:**

- Rows: 524,878
- Columns: 9
- Time period: December 2010 – December 2011

🛠️ **Tools & Technologies**

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Microsoft Excel / Power Query

🔍 **Analysis Performed**

The following exploratory analyses were performed:

- Dataset structure and data-quality checks
- Descriptive statistics
- Revenue analysis by country
- Revenue analysis by product description
- Quantity analysis by product description
- Monthly revenue trends
- Monthly quantity trends
- Monthly revenue growth
- Average Order Value analysis
- Customer identification analysis
- High-volume transaction/outlier review

📈**Key KPIs**

Metric| Value
Total Revenue| £10,642,110.80
Total Quantity Sold| 5,572,420
Total Invoices| 19,960
Average Order Value| £533.17
Identified Customers| 4,338
Unidentified Customer Records| 132,186
Unidentified Customer Records| 25.18%
UK Revenue Share| 84.59%
Top 10 Description Revenue Share| 10.84%

💡 **Key Insights**

1. UK Revenue Concentration

The United Kingdom generated approximately £9.00 million, accounting for 84.59% of total revenue. This indicates that the dataset's revenue is heavily concentrated in the UK market.

2. Monthly Revenue Variation

November 2011 recorded the highest monthly revenue at £1,503,866.78, while February 2011 recorded the lowest at £522,545.56. November revenue was approximately 2.88 times February revenue.

3. High-Volume Product Description

Paper Craft, Little Birdie recorded 80,995 units sold and generated £168,469.60 in revenue. It ranked first among the analyzed descriptions by quantity sold.

4. Customer Identification Limitation

132,186 records, representing 25.18% of the cleaned dataset, have "CustomerID = 0". Therefore, customer-level analysis should be interpreted carefully because a significant portion of records does not have an identified customer.

5. Revenue Distribution

The top 10 descriptions generated £1,153,142.32, representing 10.84% of total revenue. This indicates that revenue is distributed across a broad range of descriptions rather than being dominated by the top 10 alone.

6. Potential High-Volume Outlier

A record for Paper Craft, Little Birdie contains 80,995 units and generates £168,469.60, approximately 1.58% of total revenue. Since the record contains populated customer, date, quantity, and price fields, it should be treated as a potential outlier requiring validation rather than automatically classified as an error.

7. Monthly Revenue and Quantity Trend

Monthly revenue and quantity generally increase toward November, with November recording approximately 751,377 units and £1.50 million in revenue.

December should not be interpreted as a normal full-month decline because the dataset ends on 9 December 2011.

8. Overall Dataset Scale

The cleaned dataset contains 19,960 invoices, 5,572,420 units sold, and approximately £10.64 million in total revenue, showing substantial transaction volume across the analyzed period.

📊 **Visualizations**

The analysis includes visualizations for:

- Top 10 Countries by Revenue
- Top 10 Countries by Quantity Sold
- Top 10 Descriptions by Revenue
- Top 10 Descriptions by Quantity Sold
- Monthly Revenue Trend
- Monthly Quantity Sold Trend
- Monthly Revenue Growth Rate

📁 **Project File**

The complete Python EDA notebook is available in this repository:

"SWYNEX_Task_2_Eda.ipynb"

🎯 **Conclusion**

The exploratory analysis identified significant geographic concentration, monthly revenue variation, high-volume sales patterns, and customer-data limitations.

These findings provide a foundation for the next stage of the internship, where the analyzed data can be transformed into an interactive dashboard and further business insights.
