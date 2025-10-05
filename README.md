# RFM Analysis & Personalized Customer Messaging

This project focuses on applying Recency, Frequency, and Monetary (RFM) analysis to segment customers and deliver personalized messages based on their behavioral patterns. The analysis is performed and visualized using Tableau.

Project Overview:

The core objective is to understand customer engagement and tailor communication to different customer segments, ultimately aiming to improve retention and satisfaction. By leveraging RFM metrics, customers are categorized into distinct groups, each receiving a message designed to resonate with their specific behavior.

Key Features

•	RFM Segmentation: Customers are segmented into groups like Champions, Loyal Customers, Potential Loyalists, Promising, At Risk, Hibernating, and New Users based on their recent activity, visit frequency, and watch duration.

•	Personalized Messaging: Tailored messages are crafted for each segment to encourage desired behaviors, such as re-engagement for "At Risk" customers or continued loyalty for "Champions."

•	Detailed Segment Analysis: The project provides insights into the gender distribution and content preferences (Movies, Sports, TV Shows) within each customer segment.

•	Interactive Dashboards: Visualizations created in Tableau offer an interactive way to explore customer segments and their characteristics.

Data Sources:

The project utilizes two primary data sources:

•	StreamFlix_SegmentationTable.csv: Contains core customer behavioral data, including Customer ID, Evaluation Date, Max Visit Date, Count of Visits, and Watch Duration (in minutes).

•	StreamFlix_MessageTable: Likely contains the predefined personalized messages for each customer segment.

Metrics Analyzed

The project tracks and analyzes the following key metrics:

•	Total Customers: 300

•	Average Visit Frequency: 32.67

•	Average Watch Time (in minutes): 9,295

Customer Segments and Insights:

The following customer segments have been identified with their respective characteristics:

•	Champions: These are your most engaged and loyal customers.

o	Total: 49

o	Avg Visit Frequency: 55.92

o	Avg Watch Time: 14,016 mins

•	Loyal Customers: Highly frequent visitors with significant watch times.

o	Total: 8

o	Avg Visit Frequency: 46.00

o	Avg Watch Time: 13,806 mins

•	Potential Loyalists: Engaged customers with potential to become champions.

o	Total: 19

o	Avg Visit Frequency: 51.21

o	Avg Watch Time: 12,443 mins

•	Promising: Customers who are relatively new but showing good engagement.

o	Total: 162

o	Avg Visit Frequency: 30.71

o	Avg Watch Time: 9,111 mins

•	At Risk: Customers whose engagement is declining.

o	Total: 9

o	Avg Visit Frequency: 29.11

o	Avg Watch Time: 7,101 mins

•	Hibernating: Customers who have not engaged recently.

o	Total: 22

o	Avg Visit Frequency: 9.50

o	Avg Watch Time: 3,215 mins

•	New Users: Recently acquired customers.

o	Total: 31

o	Avg Visit Frequency: 10.61

o	Avg Watch Time: 3,440 mins

Visualizations and Dashboards:

The Tableau workbook includes several sheets and a dashboard for comprehensive analysis:

•	Dashboard: Provides an executive summary of the RFM analysis and personalized messages.

•	Segmentation: Shows the distribution of customers across different RFM segments.

•	Segment Details: Breaks down segments by gender and preferred content types (Movies, Sports, TV Shows).

•	Personalized Message: Displays the tailored messages for each customer segment.

•	Total Customers: A simple visualization of the total customer count.

•	Avg Visit Frequency: Displays the overall average visit frequency.

•	Avg Watch Time (in mins): Shows the overall average watch time.

![image_alt](https://github.com/apurbadas2311/RFM-Analysis-Personalized-Customer-Messaging/blob/main/Dashboard.png)


