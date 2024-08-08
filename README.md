# Google Business Intelligence Certificate
The Google Business Intelligence Professional Certificate course is a good choice for anyone interested in learning more about business intelligence. Both academic and practical topics are covered in the well-organized courses. In addition, the certification is competitively priced and may be completed in less than two months. The course covers the fundamentals of business intelligence (BI), the technology and tools that BI analysts frequently utilize, and the kinds of abilities required to succeed in the field as a professional. The program offers three courses: Decisions, Decisions: Dashboards and Reports; The Path to Insights: Data Models and Pipelines; and Foundations of Business Intelligence.


Certificate:
![image](https://github.com/user-attachments/assets/b29bcaf0-fc9e-4b23-9f7d-47c6e807a652)


## Capstone Project: Google Fiber - Customer Support Repeated Calls


Google Fiber serves as a case study for a telecom company with call centers in three markets. Numerous calls for support are from recurring customers in each market. A client that calls back frequently to ask for assistance with their initial problem is known as a repeat caller. Customers have occasionally called back four or five times with the same problem. The team's main objective is to interact with consumers in order to lower call numbers, raise customer happiness, and enhance operational efficiency.


The purpose of the Google Fiber customer service team is to find out how frequently customers call customer support after making their initial inquiry. By doing so, leadership will be able to assess how well the team responds to customer inquiries on the first try. Your dashboard should show that you understand this objective and give your stakeholders information about the number of repeat callers in various markets and the kinds of issues they represent. You have been requested to build a dashboard as part of the interview process that will:

+ Assist them in determining the frequency with which clients contact customer service following their initial inquiry; this will enable management to gauge the efficacy of the team's response to client inquiries.

+ Share information about the kinds of client concerns that appear to result in more follow-up calls.

+ Examine the patterns of return calls in the three distinct market cities.

+ Create charts that allow stakeholders to see trends by quarter, year, week, and month.



### Stakeholder Requirements
Reducing the number of repeat callers will enhance and optimize the overall customer experience.  Stakeholders should be able to access information regarding the number of repeat callers in various markets and the issues they indicate through the BI dashboard.  The new Business Intelligence (BI) dashboard will offer insights into the kinds of customer problems that lead to a higher number of follow-up calls.

### Project Requirements (you can look at the docx file)
Tableau will be used to develop the new BI dashboard for markets, issues, and repeat callers.  The market_1, market_2, and market_3 files, each of which represents a distinct market area, make up the repeat caller data.  The issues of the following categories are included in each market file.


| Issue  | Description                     |
|--------|---------------------------------|
| Type_1 | Account Management issue        |
| Type_2 | Technical Troubleshooting issue |
| Type_3 | Scheduling issue                |
| Type_4 | Construction issue              |
| Type_5 | Internet and Wifi issues        |

The call types for each market are as follows:

| Caller Type  | Description                    |
|--------------|--------------------------------|
| contacts_n   | Number of initial calls        |
| contacts_n_1 | Number of first repeat calls   |
| contacts_n_2 | Number of second repeat calls  |
| contacts_n_3 | Number of third repeat calls   |
| contacts_n_4 | Number of fourth repeat calls  |
| contacts_n_5 | Number of fifth repeat calls   |
| contacts_n_6 | Number of sixth repeat calls   |
| contacts_n_7 | Number of seventh repeat calls |

It is necessary to establish an ETL procedure. The several market files will be merged into a single data file via the new ETL procedure.  For the caller type, the missing data must be substituted with zero.  

Tableau will be used to construct four distinct worksheets that make up the new dashboard.

1. Trendchart of repeat callers by market
2. An KPI Performance Metric
3. Repeat callers by market and call type
4. Repeat callers by market and issue type
5. Repeat callers by day and market


### Tableau Dashboard
Tableau Dashboard Link: https://public.tableau.com/app/profile/roni.sinabutar/viz/BIGoogleFiberCustomerServiceDashboard/Dashboard

![BI_Google Fiber Customer Service Dashboard](https://github.com/user-attachments/assets/e92a819d-78aa-4e42-ba9b-2552b325b2f6)
