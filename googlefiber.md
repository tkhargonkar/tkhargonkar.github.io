## Analysing Repeat Customer Calls for Google Fiber - Capstone Project

**Project description:** 
In this case study, I am hired as a business intelligence analyst for Google Fiber's customer service team. I am tasked with producing project planning documents and a dashboard providing insights into their major business questions. This is part of the project activity for the Google Business Intelligence certificate.

### 1. Statement Of Business Task

_Provide insights into repeat customer calls for Google Fiber's customer service team._

The Google Fiber customer service team is facing repeating calls from customers, post first-contact. In order to increase customer satisfaction, mitigate the service team's workload, and improve the overall product experience, the team seeks insights into the markets, problem types, and time periods that face repeated calls - repeatedly.

### 2. Data Sources Used

Three CSV files were provided by the customer service team pertaining to three different city service areas, represented by market_1, market_2, and market_3. These datasets included information about the number of calls, number of repeat calls after first contact, problem type, and date of first contact, from January 1, 2022 till March 31, 2022 [Q1].

Problem types include the following:
   * Type_1 is account management

   * Type_2 is technician troubleshooting

   * Type_3 is scheduling

   * Type_4 is construction

   * Type_5 is internet and wifi

### 3. Documentation Of Cleaning And Manipulation Of Data

The three CSV files were merged using a SQL query in BigQuery and saved as the target table. This target table CSV file was uploaded to Tableau Public for visualisation and further analysis. Days after the first contact were labeled as 'Contact N X,' where 'X' represents the number of days since the first contact.

### 4. Supporting Project Planning Documents

The project planning documents required for this business task include the following and can be viewed below.

1. [Stakeholder Requirements Document](https://github.com/user-attachments/files/19248671/Google.Fiber.-.Stakeholder.Requirements.Document.pdf)

2. [Project Requirements Document](https://github.com/user-attachments/files/19248673/Google.Fiber.-.Project.Requirements.Document.pdf)

3. [Strategy Document](https://github.com/user-attachments/files/19248681/Google.Fiber.-.Strategy.Document.pdf)


### 5. Supporting Viz And Key Findings

The dashboard can be accessed on Tableau public [here](https://public.tableau.com/views/Project-AnalysingRepeatCustomerCallsforGoogleFiber/TablesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

Here are the key findings:

1. Market 1 recorded the highest number of first repeat calls, with "Technician Troubleshooting/Type 2" as the leading issue. Market 3 followed, where "Internet and Wifi/Type 5" was the most common problem. Market 2 also experienced a significant number of "Internet and Wifi/Type 5" issues.  

2. "Internet and Wifi/Type 5" was the most frequent issue causing repeat calls across all markets, followed by "Technician Troubleshooting/Type 2." These issues remained dominant even on the 7th day of repeat calls. 

3. Monday had the highest volume of first contact calls, while Thursday saw the most first repeat calls.  

4. March 2022 was the busiest month for customer support calls in Q1. Not enough data was provided to suggest that March's popularity is a historical trend.

### 6. Recommendations Based On Analysis

In order to improve customer satisfaction and experience, and reduce the load on the customer service team, I make the following recommensations:

1. Schedule customer service professionals during busy times, vis-à-vis Mondays and Thursdays.
   
2. Implement troubleshooting and self-help guides for products under the "Internet and Wifi/Type 5" category.
   
3. Allot highly trained technicians for Market 1, which faced the most issues with "Technician Troubleshooting/Type 2".

### 7. Key Skills Demonstrated

 ```Data Visualisation```  ```Report Writing```  ```Tableau```  ```BigQuery```
