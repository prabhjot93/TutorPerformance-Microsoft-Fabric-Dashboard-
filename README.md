# TutorPerformance-PowerBi-Dashboard-

This dashboard provides meaningful insights about training provider's performance level. It compares rating score of different tutors across intakes, training weeks, programs and uncovers trends by identifying overall session's satisfaction rate. Calculated %detractor users, %promotor users, %passive users and overall Net Performance Score to help business in making more informed data-driven decision.

Developed an end-to-end solution for ‘Performance Dashboard’ project.Especially, using Microsoft Fabric for data processing and data integration pipeline to ensure continuous flow for the dashboard.

In project, I created a new Lake House and built Dataflow to read the data from company's Lakehouse.Further designed model with Fabric Data Warehouse like staging tables, dimension and fact tables for star schema model. Used Fabric Pipeline (Azure Data Factory) to build ETL to get data loaded to your star schema in Data Warehouse.


Generated Insights about each tutor performance, including how many responses, average rating.
Insights about training performance by intakes and programs, including how many responses, average rating.
NPS score for tutor and training, how many promoters, detractors and NPS percentage. 
Promoter: 1-6, Passive: 7-8, Detractor: 9-10
Drill through to score and comment for each response.
Showed NPS and Average Score by intake, by program, by tutor, did comparison intake by intake etc.

Please check full interactive dashboard by clicking on below link.


[Click Here to view Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDA3MjJjODktYmQwYy00OWQ5LTk2ZjYtN2M4ZmJhM2E5MzUyIiwidCI6ImE4ZDQ4NGQ1LTI5OGUtNDgyMy04NjQ5LWI1MDk0MzM0ODlmZiJ9)
