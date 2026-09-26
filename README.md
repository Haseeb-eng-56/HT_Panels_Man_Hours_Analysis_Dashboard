# HT_Panels_Man_Hours_Analysis_Dashboard
This report presents the HT Panels Final Assembly Man-Hour Analysis Dashboard. It focuses on production hours, workforce utilization, reworking, and monthly efficiency. The dashboard helps monitor production performance and man-hour usage through organized monthly data and calculations.
HT Panels Final Assembly Man-Hour Analysis Dashboard
Man-Hour Analysis and Production Performance Report

**1. Introduction**

The HT Panels Final Assembly Man-Hour Analysis Dashboard is an Excel-based system developed to analyze production man-hours, workforce availability, panel production, reworking activities, and overall shop efficiency. The workbook provides a structured method for recording monthly production information and converting it into meaningful performance indicators.

The dashboard is supported by different worksheets including Master Data, Monthly Data, Monthly Production, Reworking Data, Monthly Summary, and Dashboard. These worksheets work together to provide a consolidated view of the HT Panel production performance.

**2. Purpose of the Dashboard**

The main purpose of the dashboard is to monitor and analyze the utilization of available manpower hours against the man-hours required for production and reworking activities.

The system helps in:

Monitoring monthly workforce availability
Calculating working hours
Accounting for absent hours
Considering gate-pass hours
Recording breakdown hours
Considering maintenance hours
Including overtime hours
Recording reworking hours
Calculating production man-hours
Determining the difference between available and utilized hours
Calculating monthly efficiency

**3. Dashboard Structure**

The workbook is divided into several interconnected worksheets:

Intro
Dashboard
Master Data
Monthly Data
Monthly Production
Reworking Data
Monthly Summary

Each worksheet has a specific role in the overall man-hour analysis system. The input data is organized in separate sheets, while the Dashboard and Monthly Summary present the calculated results.

**4. Master Data**

The Master Data worksheet contains the standard man-hours associated with different HT/MV panel products.

The available product categories include:

Incoming Panel
Outgoing Panel
Capacitor Control Panel
Consumer Panel
Owner
Industrial
Bus Coupler Panel
K-Electric Type A
K-Electric Type B
Cassette Type 1
Cassette Type 2
LBS

The standard man-hours are used as the basis for calculating the total production man-hours for different panel quantities.

**5. Monthly Workforce Data**

The Monthly Data worksheet contains the workforce and working-hour information for each month.

The recorded parameters include:

Month
Year
Number of employees
Shift hours per day
Total calendar days
Sundays
Public holidays
Working days
Working hours per employee
Total working hours

For example, January 2026 contains 41 employees with an 8-hour daily shift and 27 working days.

This information provides the foundation for calculating the available manpower hours.

**6. Calculation of Available Man-Hours**

The workbook considers several factors before determining the final available manpower hours.

The calculation includes:

Total Working Hours

minus/adjusted for factors such as:

Absence
Gate Pass
Breakdown
Maintenance

while also incorporating:

Overtime
Rework hours

The resulting value is recorded as Net Available Hours.

For example, the January 2026 data shows:

Total Working Hours = 8,856 hours
Absent Hours = 1,328.4 hours
Gate Pass Hours = 442.8 hours
Breakdown Hours = 177.12 hours
Maintenance Hours = 10 hours
Overtime Hours = 2,656.8 hours
Rework Hours = 75 hours
Net Available Hours = 9,479.48 hours

**7. Monthly Production Data**

The Monthly Production worksheet records the production activities carried out during each month.

The major information recorded includes:

Month
Year
FB Number
Customer Name
Description
Panel Name
Completion Percentage
Quantity
Standard Man-Hours/Product
Total Man-Hours

The total man-hours for a production activity are determined according to the quantity and applicable standard man-hours.

This allows the production department to convert the physical production quantity into measurable manpower utilization.

**8. Panel Production Analysis**

The dashboard provides a product-wise overview of production performance.

For January 2026, the dashboard shows examples such as:

Panel/Product	Total Man-Hours	Quantity
Incoming	1,650	10
Consumer Panel	145	1
Owner	508	4
Industrial	605	5
Cassette Type-1	980	8
Cassette Type-2	735	6
LBS	195	3

This product-wise analysis makes it easier to identify which panel types contributed to the overall production man-hours.

**9. Reworking Data**

The Reworking Data worksheet records activities that require additional work after the original production activity.

The sheet includes:

Month
Year
Customer
Panel Name
Panel Type
Completion Percentage
Quantity
Standard Man-Hours/Product
Total Man-Hours

Examples of reworking activities in the workbook include:

Earthswitch Pad Replacement
CT Change
Label Change
Panel Back Sheet Change
VCB Repairing
Industrial Panel Insulator Replacement

This data is important because reworking consumes additional manpower and therefore needs to be included in the overall man-hour analysis.

**10. Monthly Production Hours**

The Monthly Summary combines production and reworking man-hours.

The workbook calculates:

Production Hours = Production Man-Hours + Reworking Man-Hours

This provides a more complete picture of the manpower utilized during each month.

For example, in January 2026:

Net Available Hours = 9,479.48
Production Hours = 5,019
Difference = 4,460.48
Efficiency = 52.95%
**11. Difference Calculation**

The dashboard calculates the difference between available manpower hours and production hours.

The formula used in the Monthly Summary is:

Difference = Net Available Hours − Production Hours

A positive difference indicates that the calculated net available hours are higher than the recorded production/reworking hours for that month.

For January 2026, the difference is:

9,479.48 − 5,019 = 4,460.48 hours

**12. Efficiency Calculation**

Efficiency is one of the major performance indicators of the dashboard.

The workbook calculates efficiency using:

Efficiency (%) = Production Hours ÷ Net Available Hours × 100

The monthly efficiency values recorded in the workbook include:

Month	Efficiency
January	52.95%
February	97.88%
March	71.00%
April	75.72%
May	76.01%
June	97.46%
July	97.53%

These figures allow monthly performance to be monitored through a single measurable indicator.

**13. Monthly Performance Comparison**

The Monthly Summary provides a comparison of performance from January to July 2026.

The recorded data shows that February, June, and July have production hours close to the calculated net available hours, resulting in efficiencies above 97%.

In comparison, January has a calculated efficiency of approximately 52.95%, while March, April, and May show efficiencies of approximately 71%, 75.72%, and 76.01%, respectively.

This monthly comparison helps identify changes in manpower utilization and production performance.

**14. Dashboard Visualization**

The Dashboard worksheet provides a consolidated visual representation of the underlying data.

It includes information related to:

Absent Hours
Gate Pass Hours
Breakdown Hours
Rework Hours
Maintenance Hours
Monthly reworking
Product-wise man-hours
Product quantities
Net available hours
Production hours
Difference
Efficiency

The dashboard therefore reduces the need to manually examine multiple worksheets when reviewing overall production performance.

15. Role of Excel Formulas**
**
Excel formulas are used throughout the workbook to automate the calculations.

Important functions and calculation methods include:

SUMIFS for monthly data aggregation
IFERROR for controlled efficiency calculations
Date-related functions for calculating monthly days
Lookup-based calculations for standard man-hours
Product and monthly aggregation

For example, the Monthly Summary uses SUMIFS to obtain monthly net available hours and production hours from the respective worksheets.

This automation reduces manual calculation and helps maintain consistency in the analysis.

**16. Importance of Man-Hour Analysis**

Man-hour analysis is important for understanding how available manpower is being utilized in production activities.

It provides useful information for:

Workforce planning
Production planning
Productivity monitoring
Resource allocation
Identifying reworking requirements
Monitoring overtime
Comparing production requirements with available manpower
Measuring production efficiency

The dashboard provides a systematic approach for monitoring these factors.

**17. Benefits of the Dashboard**

The developed dashboard provides several benefits:

Centralized production information
Automated man-hour calculations
Monthly efficiency monitoring
Product-wise production analysis
Reworking analysis
Workforce utilization monitoring
Reduced manual calculations
Easy comparison between months
Better visibility of production performance
Structured data management

**18. Limitations and Data Considerations**

The analysis is dependent on the accuracy and completeness of the entered production, workforce, overtime, reworking, and other operational data.

The dashboard calculates results based on the information provided in the workbook. Therefore, accurate input data is essential for reliable performance analysis.

The workbook currently contains monthly summary data through July 2026, while the Monthly Data worksheet also contains later monthly workforce entries. Therefore, the report's summarized production-performance comparison is based on the months for which corresponding production/reworking summary data is available.

**19. Overall Findings**

The dashboard demonstrates a structured relationship between workforce availability and production requirements.

The analysis shows considerable variation in monthly efficiency. January records approximately 52.95% efficiency, whereas February reaches approximately 97.88%. June and July also record efficiencies of approximately 97.46% and 97.53%, respectively.

The inclusion of reworking hours provides a more comprehensive representation of manpower utilization because additional work is incorporated into production-hour calculations.

**20. Conclusion**

The HT Panels Final Assembly Man-Hour Analysis Dashboard provides an organized and automated method for analyzing workforce utilization, production man-hours, reworking activities, and monthly efficiency.

The workbook integrates Master Data, Monthly Workforce Data, Monthly Production, Reworking Data, and Monthly Summary into a single analytical system. The final Dashboard presents these calculations in a simplified form, making it easier to monitor production performance and compare monthly results.

Overall, the system demonstrates how Excel can be effectively used for production planning, man-hour analysis, workforce monitoring, and performance evaluation in an HT panel production environment.

<img width="1476" height="737" alt="Screenshot 2026-09-17 221745" src="https://github.com/user-attachments/assets/5f6fe6a4-0270-497f-bc32-ec1d885c7905" />
<img width="1912" height="754" alt="Screenshot 2026-09-17 221850" src="https://github.com/user-attachments/assets/c29e563b-a866-4272-8e01-ffac3fb884ae" />
<img width="1825" height="840" alt="Screenshot 2026-09-17 222030" src="https://github.com/user-attachments/assets/b6182173-016b-49c8-8c7f-f08026a19295" />
<img width="1759" height="829" alt="Screenshot 2026-09-17 222055" src="https://github.com/user-attachments/assets/7500e751-2664-4f75-b3f2-68362abb1598" />
<img width="1790" height="849" alt="Screenshot 2026-09-17 222113" src="https://github.com/user-attachments/assets/aa3542c4-cfb5-4fc6-ab02-d8c8a3b04623" />
<img width="1837" height="796" alt="Screenshot 2026-09-17 222156" src="https://github.com/user-attachments/assets/8469826b-f8f9-41cb-9ca4-83f423f970bd" />
<img width="1904" height="758" alt="Screenshot 2026-09-17 222228" src="https://github.com/user-attachments/assets/e83b4431-ba4d-426a-8a0a-4cbbc9aeceec" />
<img width="1834" height="716" alt="Screenshot 2026-09-06 013424" src="https://github.com/user-attachments/assets/78fae244-1454-473f-84ef-eca2ded26da7" />
<img width="1886" height="724" alt="Screenshot 2026-09-06 013515" src="https://github.com/user-attachments/assets/cc8f7a3b-dc94-471b-b823-cde01219e44d" />
