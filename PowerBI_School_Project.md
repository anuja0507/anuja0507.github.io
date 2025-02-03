Education domain has a significant importance in shaping effective learning experiences. 
Data analytics in education is the use of data to understand and improve educational processes, practices, and outcomes. 
It can involve different types of data, such as student demographics, attendance, grades, test scores, enrollment, behavior etc. 

Here I have come up with School performance reports for **Victoria School District(VISD)** focusing 2 key areas - **Enrollment** & **Attendance**.
Please note: This is a dummy project with name VISD and does not contain actual data of the district.

# Business goal: 
Teachers should be able to identify strengths and potential areas for improvement in terms of Enrollments & Attendance. 
The level of detail provided by the School Performance Report should support schools to improve their 
strategic planning by identifying key areas for improvement and enabling schools to access targeted supports 
for improved outcomes.\
**Audience:**
Teachers & principals.

# My Approach:

**Data Acquisition:**\
-Generated 2 years of data for 5 sample schools.

**Data Cleansing:**\
-Standardized data formats\
-Standardized data types\
-Rename columns and tables with meanigful names.

**Data Transformation:**\
-Created calculated Columns\
-Find data anomalies and data statistics (Column Profiling & values distribution)

**Data Modeling:**\
-Built a cohesive star schema model within Power BI to establish relationships between different data sets.\
-Cross filter direction is set correctly.\
-Added date table & cerated hierarchy for time intelligence calculations and marked it as a date table.

**Choose Metrics & Level of Detail:**

|Metric |Visual |Level Of Detail |
|:------|:------|:---------------|
|Number of Enrollments|KPI|Year|
|New Enrollments|Card|Year|
|Dropouts|Card|Year|
|Graduated|Card|Year|
|Total Schools|Card|Year|
|Total Students|Card|Year|
|Male Students|Card|Year|
|Female Students|Card|Year|
|Total Teachers|Card|Year|
|Enrollment by Ethnicity|Pie Chart|Year, Ethnicity|
|Enrollment by Grade|Clustered Column Chart|Year, Grade|
|Enrollment by School|Clustered Bar Chart|Year, School|
|District Attendance Rate|KPI|Year|
|Students with 100% Attendnace|KPI|Year|
|Chronic Absentism Rate|KPI|Year|
|Total Suspended|Card|Year|
|Monthly Attendance Rate|Line Chart|Year, Month|
|Monthly Absence by Category|Stacked Column Chart|Year, Month, Category|
|Highest Attendnace School|Card|Year|
|Lowest Attendance School|Card|Year|


**Data Visualization:**\
Leveraged a variety of Power BI visuals based on the type of data to present insights in a clear and engaging way and designed a user-friendly Power BI report that effectively communicated key findings.\
Slicers:\
Select year: Allow users to customize the dashboard to display data for any year\
Select School: Allow users to customize the dashboard to display data for any School

**Power BI VISD Enrollment Report:** [PowerBI_Enrollment_Overview](https://github.com/anuja0507/Portfolio-AnujaDeshpande/blob/f5ec30b5d28e483d07a0f21f74db79eb22937eca/3_PowerBI_School_Project_Enrollment_Overview.jpg)

**Power BI VISD Attendance Report:**[PowerBI_Attendance_Overview](https://github.com/anuja0507/Portfolio-AnujaDeshpande/blob/02eb7b458c3808e36514958f13b98fa330a348f2/3_PowerBI_School_Project_Attendance_Overview.jpg)


# Key Findings:

**<ins>School Insights:</ins>**
1. Identified top & low performing schools.
2. Mount carmel Middle School where enrollment is dropped compared to previous year.
3. Current year has less enrollments for Kindergarden compare to previous year. Need to see how we can improve this area.

**<ins>Student Insights:</ins>**
1. Almost 70% students are mainly from 2 ethnicities - Australian & Asian
2. Total 10 new students are added to school district current year and 3 are dropped from previous year.
3. 100% Graduation rate for 2023 school year which is an great acheivement for school District.

**<ins>Attendnace Insights:</ins>**
1. District Attendance Rate falls between 97.5% to 100% through out the year.
2. There are 76.29% students for current year with 100% Attendance.
3. There are 2% students who falls under Chronic Absentism bracket where attendance is less than 85%
4. Absent Rate is high during April to August months due to sickness.
