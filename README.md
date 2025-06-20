# Bellabeat-Case-Study
Table of content

Introduction

Phase 1: Ask - A clear summary of the business task

Phase 2: Prepare - A description of all data sources used

Phase 3: Process - Documentation of any cleaning or manipulation of data

Phase 4: Analyze - A summary of your analysis

Phase 5: Share - Supporting visualizations and key findings

Phase 6: Act - High-level recommendations based on the analysis

Introduction


Bellabeat, a high-tech manufacturer of health-focused products for women. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company. She has asked the marketing analytics team to focus on a Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices. Then, using this information, she would like high-level recommendations for how these trends can inform Bellabeat marketing strategy.

Bellabeat Products

○ Bellabeat app: The Bellabeat app connects to their line of smart wellness products.

○ Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace or clip.

○ Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep and stress.

○ Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day.

○ Bellabeat membership: Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and beauty and mindfulness based on their lifestyle and goals.

Phase 1: Ask - A clear summary of the business task
Business Task

Analyze smart device usage data in order to gain insight into how consumers use non-Bellabeat smart devices, then select one Bellabeat product to apply these insights into Bellabeat's marketing strategy.

Questions for Analysis:

What are some trends in smart device usage?

How could these trends apply to Bellabeat customers?

How could these trends help influence Bellabeat marketing strategy?

Phase 2: Prepare - A description of all data sources used
We used FitBit fitness tracker data for our case study. It's a dataset found on Kaggle and provided by Mobius.

About Dataset This dataset generated by respondents to a distributed survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring.

For this analysis I'll be using the daily and hourly data, rather than getting into detailed minute based user performance. To analyze these, I'll need to combine some tables together.

Phase 3: Process - Documentation of any cleaning or manipulation of data
For my analysis, I will use SQL to prepare, process and analyse data available and Tableau to create visualizations to share my findings with the stakeholders.

Importing datasets : FitBit Fitness Tracker Data.

Formatting Data : While importing the Date and Time data we use %m/%d/%Y %I:%M:%S %p, this will convert it to the correct formatting.

Exploring Data Checking for unique number of users in each table.


![image](https://github.com/user-attachments/assets/442a0be2-dd96-47fb-be02-be55eace2517)


![image](https://github.com/user-attachments/assets/a908d54c-9262-441c-9e0e-14c8261e5f0a)

  ![image](https://github.com/user-attachments/assets/48ebbce5-8ac6-41c3-8df3-38bffe227be4)

![image](https://github.com/user-attachments/assets/54828576-d7d8-4ee6-be1f-55fdb724893b)

![image](https://github.com/user-attachments/assets/0f63c35b-d7dd-497f-92fb-bdb02164f7e1)


![image](https://github.com/user-attachments/assets/e59bfacb-71e3-4d2b-b429-699bec9ca989)


![image](https://github.com/user-attachments/assets/82b4bc6d-220c-425b-8fdc-abd0feca9dd2)
![image](https://github.com/user-attachments/assets/c81d6a63-c8e6-4605-8085-087a45ffb169)

![image](https://github.com/user-attachments/assets/51fa53a1-1025-433c-a33f-42548f2fab8f)

Duplicates Checking for any duplicates records in the tables.

![image](https://github.com/user-attachments/assets/8d51f9c2-d088-47a3-a608-826d65e85f07)

![image](https://github.com/user-attachments/assets/c8578170-2874-4d3c-9ab3-fb3f304582e7)

![image](https://github.com/user-attachments/assets/b5f9786f-376d-4d4b-bd75-1260533fc904)
![image](https://github.com/user-attachments/assets/5951d67c-e250-4f43-b856-5f868eaddee9)

![image](https://github.com/user-attachments/assets/d82a50d8-0235-423f-a559-53ea242714d1)
![image](https://github.com/user-attachments/assets/ef2b6102-e3c8-4302-b5ce-41fbe6f1e36e)
![image](https://github.com/user-attachments/assets/20ce0966-e9e1-43cd-846d-feeedc3f42f4)

![image](https://github.com/user-attachments/assets/9f67eaec-287e-4db2-beea-b90264ebea17)

![image](https://github.com/user-attachments/assets/7e29fdab-ce18-41b8-9dc7-f83b1959e544)

