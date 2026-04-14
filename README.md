# Hospital-Readmission-Data
Hospital Readmission Data Analysis Dashboard














Prepared By:
Nagaraj Nakka

Tools Used:
 Excel | Power BI | Power Query | DAX
 
Dataset Source: Kaggle

Date: 2026



Tools						Purpose
Excel:						Data Preprocessing
Power BI:						Data Visualization
Power Query:						Data Cleaning and Transformation
DAX:						Data Analysis Calculations
Kaggle Dataset:						Hospital Readmission Data
											





Dataset Link: https://drive.google.com/file/d/16z1F5gxsFjofRf5xnZK23MJFIM3q4zeK/view?usp=sharing

Dashboard link: https://drive.google.com/file/d/1iSxR8Scs11PvWN4gKOhxIgGP3fGaea0P/view?usp=sharing

Git hub Link: https://github.com/Nagaraj0408/Hospital-Readmission-Data.git

Drive Link: https://drive.google.com/drive/folders/10CUlfRE0lxMY_2jJvtdu_dBSpx3Xm2W7?usp=sharing


1.	The Problem:
   
Large datasets containing insurance info, treatment types, and regional demographics are often siloed in different spreadsheets. This fragmentation prevents healthcare providers from seeing the "big picture," making it impossible to spot hidden patterns—such as the correlation between a specific region (e.g., South) and a specific treatment type (e.g., Medical).


3.	The Goal:
   
        To engineer a dynamic dashboard that simplifies 2,000 complex data points into a single-page visual summary, allowing users to filter by gender, treatment, and label to uncover hidden operational insights instantly. To Profile Patient Demographics for resource planning, Evaluate Insurance Coverage Trends for financial analysis, Identify High-Prevalence Medical Conditions to prioritize care, Monitor Post-Discharge Engagement to track recovery, and Analyze Seasonal Comorbidity Patterns for better peak-load management.


5.	Dataset Description:
   
The project utilizes a Hospital Readmission Dataset comprising 2,000 unique patient records, designed to track the journey of patients from admission to post-discharge follow-up.

	Patient id
	Admission Data
	Season
	Age
	Gender
	Region
	Primary Diagnosis
	Comorbidities Count
	Lenth of Stay
	Treatment Type
	Medications Count
	Followup Visits Last Year 
	Prev Readmission
	Insurance Type
	Dischare Disposition
	Readmission Risk Score

These variables help identify patterns Hospital Readmission Data.

Data Diagnostics: A Multi-Dimensional Dashboard of Patient Outcomes

1)	Core Patient Metrics (KPIs):
   
Located at the top center, these cards provide an immediate snapshot of the dataset size. It highlights a total of 2K patients, with a breakdown showing a slightly higher female population (4.2K) compared to males (3.8K), establishing the scale of the study.

3)	Insurance Type Analysis (Bar Chart):
   
This horizontal bar chart categorizes patients by their primary coverage. It reveals that Private Insurance is the leading provider (1.0K patients), followed by Medicaid (0.5K), which helps in understanding the financial demographic of the facility.

5)	Primary Diagnosis Distribution (Treemap):
   
The Treemap visualizes the most frequent reasons for admission. Diabetes (433) and Hypertension (395) emerge as the dominant health challenges, indicating that the hospital’s primary workload involves managing chronic conditions.

7)	Follow-up Visit Engagement (Donut Chart):
   
This chart tracks patient adherence to post-discharge care. A significant 47.7% of patients completed two follow-up visits, while smaller segments show varying engagement levels, providing a clear metric for patient recovery monitoring.

9)	Regional Patient Volume (Column Chart):
    
This visual segments the population by geographic location. The South region accounts for the highest volume (464 patients), whereas the Central region has the lowest (259), guiding decisions on where to allocate community health resources.

10)	Previous Readmission Trends (Pie Chart):
    
The pie chart analyzes historical patient data to identify re-entry patterns. With 64% of patients having zero previous readmissions, the data suggests that the majority of the current records represent new or successfully managed cases.

11)	Treatment Type Frequency (Column Chart):
    
This chart illustrates the methods used to care for patients. Medical treatment (829) is the most common intervention, significantly outperforming surgical and interventional methods, highlighting a preference for non-invasive care.

4.	Conclusion
   
This project demonstrates how Power BI can be used to transform raw data into meaningful insights using data modeling, DAX, and interactive dashboards.

