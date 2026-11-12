Consumer Complaint Monitoring and Response Dashboard

Project overview
This project looks at 62,516 consumer complaints about Bank of America that were collected by the Consumer Financial Protection Bureau (CFPB) between 1 May 2017 and 28 August 2023. I cleaned and checked the data, calculated the KPIs, and built a four-page Power BI dashboard so that stakeholders can follow complaint trends, the most reported products and issues, company response categories, and how long it takes the CFPB to forward complaints to the company.

A complaint is an issue reported by a consumer. It does not prove misconduct, and I kept every finding tied to the data.

Business questions I worked on
How did complaint volumes change from 2017 to 2023?
Which financial products and issues are reported most?
How do issues differ between products?
How long does the CFPB take to forward a complaint to the company?
Which company response categories appear most often?
What percentage of complaints have a recorded timely response?
How have patterns changed over time?

Tools
Power BI Desktop (dashboard, DAX measures and columns)
Excel (viewing the original data)
Python and pandas (the cleaning script)

Folder structure
Week4_Consumer_Complaints_DataAnalytics/
├── README.md
├── 01_Data/
├── 02_Data_Cleaning/
├── 03_KPIs_and_Scripts/
├── 04_Dashboard/
├── 05_Insights/
├── 06_Evidence/
├── 07_Presentation/
└── 08_Social_Posts/

01_Data: the original Excel file (unchanged), the data dictionary, and the cleaned CSV.
02_Data_Cleaning: the data quality documentation and the cleaning script.
03_KPIs_and_Scripts: the KPI definitions and calculations, and the DAX measures.
04_Dashboard: the Power BI file and screenshots of the four pages.
05_Insights: my business insights and recommendations.
06_Evidence: screenshots of my data checks, my change log, and my contribution notes.
07_Presentation: my recorded presentation.
08_Social_Posts: links to my LinkedIn and X posts.

How to open the dashboard
Install Power BI Desktop (free).
Open the .pbix file in the 04_Dashboard folder.
If Power BI asks for the data location, click Transform data > Data source settings and point it to the file in 01_Data.

Method
Inspect: I checked the structure, column types, unique Complaint IDs, duplicates, missing values and date ranges.
Clean: I handled blanks by their meaning, standardised one category, and added year, month, quarter and forwarding-interval fields. The original file was kept unchanged.
KPIs: I defined and calculated 12 KPIs with DAX.
Dashboard: I built four pages: Executive Complaint Overview, Product and Issue Analysis, Company Response Analysis, and Complaint Timeline Analysis.
Insights: I wrote six findings and four recommendations from the results.

Main results
Checking or savings accounts make up 39.7% of complaints. The top four products make up 88.5%.
The most reported issue is "Managing an account" (15,109 complaints, 24.2% of all).
96.06% of complaints with a Yes or No answer were marked as timely, with 1,494 complaints still in progress.
The median forwarding interval is 0 days and the average is 1.22 days. 623 complaints (1.0%) took more than 25 days.
Complaints rose each year from 2019 to 2022, and July 2023 was the busiest month with 1,749 complaints.

Assumptions
Date submitted is when the CFPB received the complaint. Date received is when the CFPB sent it to the company.
A blank timely response means the complaint is In progress, so it is not counted as No.
Blank sub-issues and sub-products are shown as Not specified, and blank public responses as Not provided.

Limitations
2017 starts in May and 2023 ends in August, so these years are not complete.
The forwarding interval is the CFPB's time to forward a complaint, not the company's response time.
A recorded company response does not prove a complaint was resolved.
About 17% of sub-issues are blank.
The data has no complaint narratives and covers one bank only.

Documentation
Data quality documentation
KPI definitions and calculations
Business insights and recommendations

My contribution
I loaded the data into Power BI, checked it for duplicates, missing values and valid dates, created the DAX columns and measures, built and formatted the four dashboard pages, and fixed issues after reviewing the results. I cleaned the script, did the DAX formulas and drafted the documentation. 

Data source
Consumer Complaints on Financial Products and Services, Bank of America (2017 to 2023). Data provider: Consumer Financial Protection Bureau (CFPB), supplied by AnalystLab Africa.# Week-4-Complaints-Dashboard
