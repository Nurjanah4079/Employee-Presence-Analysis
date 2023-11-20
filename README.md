# Employee-Presence-Analysis

## **Background Case**

Finale an HR manager faces challenges in managing and understanding employee attendance data in his company. Previously, this process involved manual processing of complex and large Excel files, causing complexity and high time consumption. Finale aims to enhance efficiency and understanding by adopting a data dashboard to analyze employee attendance, work-from-home trends, and sick leave percentages.

## **Source Data**

The primary data source is an open-source Excel file obtained from a REAL dataset [link](https://files.codebasics.io/uploads/resources/resume-project-data-analytics/Attendance%20Sheet%202022-2023_Masked.xlsx?Expires=1700505897&Signature=XH8gmUKHN-Wwz330JVmBsNwPtru3T-5SBMS0YKnLA2zBTtG9pVOL6TGJ3fEPWRdGem0zcj8hfrU9W3M4L~8iDu8-f1lOdgEJ8e0Lc53LfoYTdZJmxejP~-Slca3Kg4Uoh2N9WhqCUddvOUzejfz11s1P4558~CMWh2QlRV6Ec1IKRxGpqxs0bEcevo99J8~Xpd8JuKPv2IkACYQ8dwD9a4SYcYAHqcLkn-GDElg5D2II-5u-Jr1AghkbS7ZHoOHeQAcMLLjy5s~XOL5mjXyChBJne1muhj~JYDGeos-UbySGUeTKb3G6PbiUIoJyY2FPbzwIKytcIGescJEQtEdYWA__&Key-Pair-Id=K2RNEYYX7N2F8M) for employee attendance from a company named AtliQ. The data includes information on employee attendance, including attendance percentages, work-from-home habits, sick leave, and more.

## **Data Transformation**

- Extracting relevant fields such as employee names, presence, work-from-home, and sick leave information for focused analysis.
- Integrating additional data points, including dates, days of the week, and specific employee details, to enhance the granularity of the dataset.
- Add calculated fields for metrics such as attendance percentage (presence, work-from-home, and sick leave), enabling a deeper understanding of employee attendance dynamics.
- Remove Week Off and etc to align the dataset with the calendar to accurately represent workdays and facilitate date-based analysis.

## Dashboard

- Importing Excel data into Power BI starts the visualization process.
- Insights into presence, work-from-home, and sick leave patterns are delivered through visual cards and tables.
- Create interactive line charts to represent presence, work-from-home and sick leave trends.
- Bar charts are used to visually depict the percentage of presence, work-from-home, and sick leave by day.
- Create a calculated month-over-month.
- Create filter.

[Link](https://app.powerbi.com/reportEmbed?reportId=8557150d-3d9d-4076-9dea-1be9675002bd&autoAuth=true&ctid=3750697d-29e2-445d-afe9-19ea7c9da124)

## Result

- Observe a decreasing trend in presence leading up to June.
- Observe a increasing trend in work-from-home and sick leave leading up to June.
- Highlighting employee presence based on specific days of the week, with Monday having the highest presence.
- Highlighting employee work-from-home  on specific days of the week, with Friday having the highest work-from-home.
- Highlighting employee sick leave based on specific days of the week, with Monday having the highest sick leave.
- Sending notifications via email if presence falls below 80%.
- Automatic data updates, including notifications.
