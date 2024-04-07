# PowerBI_WaveX_Project
Creating an Interactive Sales and HR Dashboard with Power BI                
Power BI is a powerful business intelligence tool that enables interactive data visualization and insightful analytics. In this project,  will walk through the end-to-end process of building an interactive Sales and HR dashboard in Power BI Desktop and publishing it online. 

Data Gathering and Import :                        
The first step is gathering relevant data and business requirements. For this project, used sample sales data for a fictional company WaveX Watercraft provided in Excel, text and PDF formats.           

Data Transformation :                              
With the raw data imported, we now clean and transform it to prepare for analysis. Key steps include:
* Renaming tables for clarity
* Removing unnecessary rows
* Promoting headers
* Unpivoting columns
* Splitting columns like name into first and last
* Merging columns like first and last name
* Replacing text values
* Changing data types

Data Modeling :              
Next,  build relationships between the tables to create a star schema model. The core Fact table is the Sales table, which connects to supporting Dimension tables like Category, Product, and Distributor.
Also, created new calculated columns and measures using DAX to derive additional insights.

Data Visualization and Reporting :             
With properly modeled data, we can now visualize it effectively. We design two reports:
1) Sales Report :                         
* This shows KPIs like total revenue and interactive charts for category sales, top distributors, sales trends and forecasts. It provides a 360-degree view of the company's sales performance.                     
* Top Distributors Column Chart                  
This multiple column chart compares top distributors by sales price and cost price, illuminating the most profitable partnerships.                 
* Sales by Payment Method Donut Chart             
This donut chart provides a breakdown of total sales by the payment method used - cash, credit card, wallet etc. It enables analyzing which payment types comprise what percentage of overall revenue.
* Sales by Category Bar Chart                        
This stacked bar chart shows total sales broken down by product category. It enables analyzing which categories drive the most revenue. The chart has conditional formatting to highlight top performers.
* Sales & Forecast Line Chart                                        
The line chart shows overall sales by year. A forecast line projects the next two years based on historical data. This predicts future performance and helps planning.

2) HR Report :                                    
* This focuses on HR metrics like employee demographics, job satisfaction, and promotion status. Visualizations include cards, pie charts, a matrix, and gauges.
* Q&A Visualization                             
The Q&A card enables intuitive querying of the dataset through natural language questions. Some examples:              
"What is the average employee age?"                       
"How many employees have 5 or more years of experience?"                    
"Show average job satisfaction by department"                     
Users can quickly get answers and discover insights without needing to know the data structure. It opens self-service analytics to a wider audience.            
The Q&A visual democratizes data access in a simple conversational interface. It allows report consumers to freely explore information relevant to their interests.

Key Benefits :                    
* Interactive visualization uncovers data insights
* Modeling enhances analysis
* Powerful DAX calculations
* Real-time data refresh
          
  









