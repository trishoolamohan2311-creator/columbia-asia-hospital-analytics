# Columbia Asia Hospital Analytics

## Project Overview

A hospital analytics project using SQL and Power BI to analyze patient visits, department performance, doctor revenue, waiting time, patient satisfaction, and revenue trends.

The project focuses on three business objectives:

- Assess hospital revenue generation
- Identify departments for new doctor hiring
- Develop patient discount strategies

## Business Objectives

- Analyze revenue by department and over time
- Identify departments with high patient demand and operational pressure
- Evaluate doctor-level revenue contribution
- Analyze patient demographics and department preferences
- Study waiting time and its relationship with patient satisfaction
- Develop targeted discount strategies for selected patient segments

## Tools & Technologies

- SQL
- Power BI
- DAX
- Power Query
- Excel

## Dashboard

The Power BI report contains three dashboards.

### Main Dashboard

Provides hospital-level KPIs for:

- Total Doctors
- Total Patients
- Total Revenue
- Average Waiting Time
- Average Patient Bill
- Average Satisfaction Score

### Doctors Dashboard

Analyzes:

- Doctor revenue contribution
- Top revenue-generating doctors
- Patient distribution by gender
- Doctor-level performance

### Patients Dashboard

Analyzes:

- Patient age groups
- Gender distribution
- Department-wise patient visits
- Waiting time
- Patient satisfaction

## Data Model

The Power BI model uses four main tables:

- `Doctors_Patients`
- `Hospital_ER`
- `Calendar`
- `visiting_hours`

The tables are connected using patient, doctor, and date fields. Calculated columns and DAX measures were used for the dashboard analysis.

## Analysis Performed

### Patient Analysis

- Age Group Distribution
- Gender Distribution
- Department Preference
- Waiting Time & Satisfaction Analysis
- Patient Demographic Analysis

### Department Analysis

- Patient Visits by Department
- Revenue Contribution
- Average Waiting Time
- Department Performance

### Doctor Analysis

- Top Revenue-Generating Doctors
- Doctor Revenue Contribution
- Male-Female Patient Distribution
- Doctor Performance Comparison

### Revenue Analysis

- Revenue by Department
- Monthly Revenue Trends
- Revenue Concentration
- Revenue Performance

## Advanced SQL Analysis

- Top Revenue-Generating Doctors
- Doctor Diversity Analysis
- Gender Ratio Analysis
- Department Performance
- Waiting Time Analysis
- Satisfaction Score Analysis
- Male-Female Revenue Ratio by Department

## Key Findings

- **Orthopedics** generated the highest departmental revenue at **₹17.29M (34%)**.
- **General Practice** recorded the highest patient volume with **7,240 visits**.
- **Patients aged 36–60** formed the largest age group, accounting for **31.7% of visits**.
- **Neurology** recorded the highest average waiting time at **36.8 minutes**.
- Patient satisfaction showed a **slight decline as waiting time increased**.
- **Dr. Smith** generated the highest revenue among the Top 5 doctors, contributing **40.5%**.
- **Orthopedics and General Practice** contributed over **66% of total revenue**.
- Monthly revenue declined from **$30.5M to $22.6M** during the analyzed period.
- Male and female patient distribution remained **relatively balanced** across departments and doctors.

## Business Recommendations

- Prioritize staffing in **General Practice and Neurology** based on patient demand and waiting time.
- Optimize appointment scheduling to reduce patient waiting time.
- Monitor patient satisfaction alongside service performance.
- Allocate resources based on patient demand and revenue contribution.
- Use targeted discounts for **frequent visitors, senior citizens, and patients with low satisfaction**.
- Monitor revenue trends and key operational KPIs regularly.

## Dashboard Screenshots

### Main Dashboard

![Main Dashboard] <img width="890" height="502" alt="image" src="https://github.com/user-attachments/assets/556c9c21-1352-4399-8bd9-1c3cfeba8271" />


### Doctors Dashboard

![Doctors Dashboard] <img width="889" height="500" alt="image" src="https://github.com/user-attachments/assets/6f6363fd-bb72-4f8e-898b-2f8cfd3ba3c7" />


### Patients Dashboard

![Patients Dashboard] <img width="888" height="501" alt="image" src="https://github.com/user-attachments/assets/5fa58c6a-55c5-4bc6-89d5-d417ed6f33f2" />


## Project Files

- Power BI Dashboard — `.pbix`
- SQL Analysis — `.sql`
- Project Documentation — `.docx`
- Project Presentation — `.pptx`
- Dashboard Screenshots — `.png`
