# Tokyo 2020 Performance Metrics Analysis -- [Microsoft Azure Project]

------------------------------------
### Tools Used:-
------------------------------------

Microsoft Azure: A cloud computing service offering various resources like virtual machines, databases, and storage solutions, enabling scalable and reliable infrastructure for your project.

Data Factory: A cloud-based data integration service that allows you to create, schedule, and orchestrate data workflows, facilitating data movement and transformation across various sources and destinations.

DataBricks: A unified analytics platform built on Apache Spark, offering collaborative data science and machine learning capabilities, along with scalable data processing and analytics.

Blob Storage Gen 2 Account: Azure Blob Storage is a scalable object storage solution that allows you to store and manage unstructured data. Gen 2 introduces features like hierarchical namespaces, ensuring better performance and compatibility with existing Azure storage features.

Synapse Analytics: A cloud-based analytics service for big data and data warehousing workloads. Synapse Analytics integrates various analytics components like data integration, big data analytics, and data warehousing into a single platform, enabling seamless data analysis and insights generation.

Virtual Machine (VM): Azure Virtual Machines provide scalable compute resources in the cloud. In this case, a VM is utilized to host Power BI, a business analytics tool for creating interactive reports and dashboards, allowing for insightful visualization and analysis of the project's data.

------------------------------------
### TABLE OF CONTENTS:-
------------------------------------

- [PROBLEM STATEMENT](#problem-statement)
- [PROJECT SUMMARY](#project-summary)
- [KPI REQUIREMENT](#kpi-requirement)
- [CHARTS REQUIREMENT](#charts-requirement)
- [DASHBOARD](#dashboard)
- [CONCLUSION](#conclusion)


------------------------------------
### PROBLEM STATEMENT
------------------------------------

The Tokyo Olympics Analysis Project seeks to analyze a comprehensive dataset of over 11,000 athletes, 47 disciplines, and 743 teams participating in the 2021 (2020) Tokyo Olympics. With details on athlete profiles, coach information, team compositions, and gender-specific entries, the project aims to uncover insights on performance trends, team dynamics, gender representation, and predictive modeling. Using advanced analytical tools like Microsoft Azure, Data Factory, DataBricks, Blob Storage Gen 2 Account, Synapse Analytics, and Power BI Virtual Machines, the project aims to inform decision-making and drive improvements in training and coaching strategies for stakeholders, organizers, and enthusiasts.

------------------------------------
### PROJECT SUMMARY
-----------------------------------
### Data Analysis on Microsoft Azure Cloud Platform:-

In this project, I leveraged the Microsoft Azure Cloud Platform to execute a comprehensive data analysis workflow as a data analyst. The primary tools and services used were Azure Data Factory, Azure Blob Storage, Azure Databricks, Azure Synapse Analytics, Virtual Machines (VMs), and Power BI. Here's a brief overview of the process and how each component was utilized:

#### 1. Data Ingestion and Storage:-

=> Data Ingestion with Azure Data Factory.

• I utilized Azure Data Factory to fetch data from an external resource, specifically GitHub.

• During the import process, the data format was converted from Excel to CSV to ensure compatibility and ease of use.

• A Data Factory Pipeline was created to automate this data ingestion and transformation process.

=> Data Storage in Azure Blob Storage:-

• The transformed CSV data was stored in Azure Blob Storage Gen 2 Account.

• Two repositories were created within the Blob Storage: one for raw data and another for clean data.


#### 2. Data Cleaning and Transformation:-

=> Data Cleaning with Azure Databricks.

• The raw data was cleaned using Azure Databricks, a powerful analytics platform that integrates with big data technologies.

• Using PySpark, I processed and transformed the raw data, addressing any data quality issues.

• The cleaned data was then stored in the Clean Data repository in Azure Blob Storage.


#### 3. Data Analysis and Visualization:-

=> Data Analysis with Azure Synapse Analytics

• Azure Synapse Analytics was used to analyze the clean data.

• By writing and executing SQL queries, I extracted meaningful insights and conducted thorough data analysis.


#### 4. Visualization with Power BI:

• To visualize the insights gained from the analysis, I used a Virtual Machine (VM) to connect the clean data from Azure Synapse Analytics to Power BI.

• In Power BI, I created various charts, graphs, and KPIs (Key Performance Indicators) to represent the data visually.

• These visualizations helped to highlight key points and trends within the data, making it easier to understand and interpret the findings.


<img width="1446" alt="Screenshot 2024-03-09 at 9 39 46 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/a0f1f133-333b-4fe8-b669-8c3795d863fe">

------------------------------------
### KPI REQUIREMENT
------------------------------------

#### Total Disciplines:-

=> This KPI measures the number of unique sporting disciplines represented in the Tokyo Olympics dataset. It provides an overview of the diversity of sports showcased in the event and helps in understanding the breadth of athletic competition.

<img width="92" alt="Screenshot 2024-06-01 at 9 23 21 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/12b3c4a5-34a9-40b3-b359-42fd7523c2b5">

#### Total Players:-

=> This KPI quantifies the total number of athletes participating in the Tokyo Olympics across all disciplines. It serves as a fundamental metric for assessing the scale of athlete involvement and the overall scope of the event.

<img width="95" alt="Screenshot 2024-06-01 at 9 23 49 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/d470dc1f-590d-4674-b997-37402ed86cdf">

#### Total Countries:-

=> This KPI indicates the total count of countries represented by athletes in the Tokyo Olympics. It offers insights into the global reach and inclusivity of the event, highlighting participation from diverse nations around the world.

<img width="101" alt="Screenshot 2024-06-01 at 9 24 11 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/ca8db785-4966-4dd3-888d-09ec5a4d71e3">

#### Total Coaches:-

=> This KPI tracks the number of coaches involved in guiding and supporting athletes across different disciplines. It provides an understanding of the coaching infrastructure and its role in athlete development and performance.

<img width="99" alt="Screenshot 2024-06-01 at 9 24 39 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/2d78701d-00fd-4dcd-a239-05ae12a1bd7d">

#### Total Gold:-

=> This KPI tallies the number of gold medals won by athletes or teams in various disciplines. It serves as a crucial indicator of success and excellence, reflecting the performance of nations and athletes at the highest level of competition.

<img width="97" alt="Screenshot 2024-06-01 at 9 25 02 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/0e89ea1b-fa27-4d75-a9db-33894f794576">

#### Total Medals:-

=> This KPI aggregates the total number of medals (gold, silver, and bronze) awarded to athletes or teams across all disciplines. It offers a comprehensive view of overall performance and achievement, facilitating comparisons between nations and tracking progress over time.

<img width="100" alt="Screenshot 2024-06-01 at 9 25 25 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/c62b4c5b-7fac-46e2-82f8-c5681169a9bb">

------------------------------------

<img width="744" alt="Screenshot 2024-06-01 at 9 27 33 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/5a97540e-beb2-485b-9953-f1adf958dd4b">

------------------------------------
### CHARTS REQUIREMENT
------------------------------------

#### Top 5 Discipline - Male and Female Players:-

=> This chart visualizes the top five sporting disciplines based on the number of male and female players participating. It provides insights into the gender distribution across different sports, highlighting the popularity and inclusivity of each discipline.

<img width="226" alt="Screenshot 2024-05-26 at 5 48 46 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/a242f4ab-eb5c-4351-9721-a8c9432e447d">

#### Top 5 Countries - Total Medals:-

=> This chart displays the top five countries based on the total number of medals won across all disciplines. It offers a comparative view of nations' performance in terms of medal count, showcasing the leading contenders in the medal standings.

<img width="232" alt="Screenshot 2024-05-26 at 5 49 34 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/bffb0e3c-3ee7-4d67-8ee0-789e964c4a2d">

#### Top 10 Countries - Top High Ranks:-

=> This chart showcases the top ten countries with the highest overall rankings in the Tokyo Olympics. It ranks countries based on their cumulative performance across all disciplines, reflecting the most successful nations in the event.

<img width="241" alt="Screenshot 2024-05-26 at 5 50 22 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/740c34e7-2f79-4fcd-a13b-7f9c53b8c562">

#### Top 5 Countries - Total Gold, Bronze, and Silver:-

=> This chart presents the top five countries based on the distribution of gold, silver, and bronze medals won. It provides insights into each nation's strengths across different medal categories, highlighting their overall dominance or specialization.

<img width="226" alt="Screenshot 2024-05-26 at 5 51 26 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/d1b7c0f9-5e69-4b07-b0e7-6b51c6ed91cf">

<img width="235" alt="Screenshot 2024-05-26 at 5 52 07 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/b5c34794-71b2-4d96-83e8-721a66e678b9">

#### Top 10 Countries - Bottom Worst Ranks:-


=> This chart visualizes the bottom ten countries with the lowest overall rankings in the Tokyo Olympics. It identifies countries with relatively poor performance across multiple disciplines, offering insights into areas for improvement or investment in sports development.

<img width="235" alt="Screenshot 2024-05-26 at 5 52 47 PM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/2e1243a3-fcb1-4800-884e-feaadc3bbb9a">

--------------------
### Dashboard 
____________________

<img width="747" alt="Screenshot 2024-06-01 at 9 30 53 AM" src="https://github.com/suraj-kumar-jha/Tokyo_2020_Performance_Metrics_Analysis--Microsoft_Azure_Project/assets/155900363/4d35c1c9-42ab-45bc-8148-402b519dd198">


-------------------
### CONCLUSION
___________________

Þ Utilized Azure Data Factory for efficient data ingestion and transformation.

Þ Converted data from Excel to CSV format during import to ensure compatibility.

Þ Employed Azure Blob Storage Gen 2 Account to store both raw and clean data.

Þ Created separate repositories for raw and clean data, enhancing data management.

Þ Leveraged Azure Databricks and PySpark for comprehensive data cleaning.

Þ Transformed raw data into clean, high-quality datasets for further analysis.

Þ Used Azure Synapse Analytics to perform in-depth data analysis with SQL.

Þ Extracted meaningful insights and identified key trends from the clean data.

Þ Connected clean data to Power BI via a Virtual Machine for advanced visualization.

Þ Developed various charts, graphs, and KPIs to represent data insights visually.

Þ Created impactful visualizations that highlighted key points and facilitated data interpretation.

Þ Demonstrated the integration and synergy of Microsoft Azure's cloud services.

Þ Achieved a streamlined and efficient end-to-end data analysis workflow.

Þ Generated actionable insights that aid in decision-making.

Þ Enhanced understanding of data through effective visualization techniques.

Þ Enabled better business strategy formulation through data-driven insights.

Þ Improved data accessibility and management for future analytical needs.

Þ Provided a scalable solution for handling large datasets efficiently.

Þ Facilitated timely and informed decision-making based on real-time data analysis.

```

```

