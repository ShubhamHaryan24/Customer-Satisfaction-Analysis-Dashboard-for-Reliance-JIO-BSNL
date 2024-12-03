# Customer-Satisfaction-Analysis-Dashboard-for-Reliance-JIO-BSNL

![image](https://github.com/user-attachments/assets/0c5f512b-0a19-4c85-91a9-db83840b4245)


![image](https://github.com/user-attachments/assets/7bc72a70-702c-460e-975e-52ff1f38a429)


Presented by:
Shubham Manohar Haryan

Data Analyst

Mumbai | +91-9029697236 | haryanshubham57@gmail.com

---

**Objective:-**

To develop an interactive dashboard that utilizes Business Intelligence Excel, Power BI, MS Office Word, MS Office PowerPoint to analyze customer satisfaction data for a telecom company. The goal is to identify key drivers of customer satisfaction and dissatisfaction, enabling the company to enhance service quality and customer experience.

---

**Data Overview**

The dataset organized into for key tables: Customers, Surveys, Support Tickets and Service Usage.

Customers- CustomerID | Name | SubscriptionPlan | City | JoinDate

Surveys- SurveyID | CustomerID | SurveyDate | SatisfactionScore | Feedback 

Support Tickets- TicketID | CustomerID | TicketDate  | IssueType | Status | ResolutionTime (hours) 

Service Usage- UsageID | CustomerID | DataUsage (GB) | CallDuration (mins) | LastUsageDate

---

**Data Modelling**

![image](https://github.com/user-attachments/assets/49f0f9dc-0272-4798-87c6-81850cfb2829)

---

**Data Visualization**

Data Visualization report display below charts for the final interactive dashboard view

• Slicers • KPI • Funnel • Map • Pie chart • Donut chart • Line chart • Column chart • Treemap • Waterfall chart

---

**DAX measures used**

1. Average Satisfaction Score
   
3. Total Number of Surveys
4. Number of Resolved Support Tickets
5. Average Resolution Time
6. Customer Satisfaction Based on Subscription Plan
7. Ticket Resolution Time for Network Issues
8. Percentage of Resolved Tickets

---

**Insights**

1) Customer Satisfaction Trends- Customers with issues related to signal strength and network issues tend to give lower satisfaction scores. For instance, surveys with feedback like "frequently dropped calls" or "poor signal strength" generally have low ratings (1 to 3). Customers with issues on billing queries also reported moderate satisfaction (around 5-6). Meanwhile, customers praising data plans or network quality generally provide higher satisfaction scores (8 to 10).

2) Customer Service Performance- The resolution time for customer support queries plays a role in overall customer satisfaction. Tickets marked as unresolved often lead to low satisfaction scores in the surveys. It appears that unresolved issues have a direct correlation with low satisfaction scores, suggesting that faster issue resolution is key to improving customer experience.

3) Impact of Survey Feedback on Service Improvement- Feedback points, such as frequently dropped calls, network issues, and billing confusion, appear frequently across both support tickets and surveys. This suggests recurring problems that need to be prioritized for service improvements. Addressing these issues could potentially boost customer satisfaction and reduce the volume of support tickets related to these problems.

---
