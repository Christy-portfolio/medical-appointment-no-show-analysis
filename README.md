# medical-appointment-no-show-analysis

An analysis of medical appointment no-shows using Microsoft Excel. This project examines 110,522 appointment records to
identify patterns and trends in missed appointments, investigate factors associated with patient attendance, and generate 
data-driven insights and recommendations to support better appointment management.

# Medical Appointment No-Show Analysis

## Project Overview

This project analyses medical appointment records to understand patterns associated with missed appointments (no-shows).
Using Microsoft Excel, I explored patient demographics, appointment scheduling patterns, health conditions, and SMS reminders 
to identify factors associated with attendance and non-attendance.

## Project Objectives

- Identify patterns in medical appointment no-shows.
- Examine how age groups relate to appointment attendance.
- Investigate the relationship between SMS reminders and no-shows.
- Analyse the effect of appointment lead time on attendance.
- Explore differences in no-show rates across weekdays and patient characteristics.
- Provide insights that could help improve appointment management.

## Dataset Description

- Source: Kaggle – Medical Appointment No Shows
- Original Records: 110,527 appointments
- Records After Cleaning: 110,522 appointments
- Unique Patients: 62,299

## Tools Used

- Microsoft Excel
- Excel Pivot Tables
- Excel Charts
- Excel Dashboards
- Data Cleaning and Analysis

## Data Cleaning and Preparation

The dataset was cleaned and prepared using Microsoft Excel. The following activities were carried out:
- Converted date fields into appropriate date formats.
- Separated scheduled dates and times.
- Removed five records where the scheduled date was later than the appointment date.
- Reviewed age values and corrected an invalid negative age.
- Corrected neighbourhood names affected by encoding issues.
- Renamed the Handcap column to Disability.
- Created additional columns, including:
	- **Age Group**
	- **Day of Week**
  - **Appointment Month**
  - **Lead Time Days**
  - **Lead Time Group**

## Business Questions

The analysis focused on the following questions:
- Does receiving an SMS reminder relate to appointment attendance?
- Which weekday has the highest no-show rate?
- Which age groups are more likely to miss appointments?
- Do patients with selected health conditions show different attendance patterns?
- What are the monthly trends in appointment no-shows?
- Does the time between scheduling and appointment dates affect attendance?
- Which grouped neighbourhood category has the highest no-show rate across weekdays?

## Key Findings

### SMS Reminders and Attendance
-	Appointments without SMS reminders had a 16.7% no-show rate.
-	Appointments with SMS reminders had a 27.6% no-show rate.
-	This indicates an association, not proof that SMS reminders increase missed appointments.

### Age Group Analysis

-	Patients aged 18–34 recorded the highest no-show rate at 23.98%.
-	Patients aged 65 and above recorded the lowest no-show rate at 15.50%.

### Appointment Lead Time

- Same-day appointments recorded a 4.65% no-show rate.
-	Appointments scheduled 1–7 days ahead recorded 24.15%.
-	Appointments scheduled 8–30 days ahead recorded 31.72%.
-	Appointments scheduled 31 days or more ahead recorded 33.00%.

No-show rates increased as the time between scheduling and appointment dates increased.

### Health Conditions

- Patients without hypertension had a 20.90% no-show rate, compared with 17.30% among those with hypertension.
- Patients without diabetes had a 20.36% no-show rate, compared with 18.00% among those with diabetes.
- Patients with disabilities recorded a 23.62% no-show rate, compared with 20.23% among those without disabilities.

### Monthly Trend

- **April 2016:** 19.57%
- **May 2016:** 20.78%
- **June 2016:** 18.46%

The monthly no-show rates showed relatively small variations.

### Weekday and Grouped Neighbourhood Analysis

-	The Pediatrics-labelled group recorded the highest identified no-show rate of 24.24% on Tuesday.
-	Tuesday also showed notable no-show patterns across several grouped categories.

Note: The six categories used in this analysis were created by grouping neighbourhoods. They are not actual hospital
departments. Findings from this analysis should therefore be interpreted cautiously.

## Recommendations

- Consider additional reminders and follow-up for appointments scheduled well in advance.
- Explore targeted engagement strategies for younger patients.
- Investigate possible barriers to attendance among patients with disabilities.
- Review SMS reminder strategies to understand why recipients recorded a higher no-show rate.
- Use appointment scheduling patterns to support better patient follow-up and appointment management.

## Limitations

- The analysis identifies associations and patterns; it does not establish causation.
- The dataset covers appointments from April to June 2016, limiting the monthly trend analysis.
- The department categories used in the analysis were created by grouping neighbourhoods and do not represent actual hospital
  departments.
- The dataset does not establish why patients miss their appointments or why SMS recipients have higher no-show rates.

## Project Files

The Excel workbook contains the following worksheets:
-	[Raw Data](https://github.com/Christy-portfolio/medical-appointment-no-show-analysis/blob/main/Raw%20Data.xlsx)
-	Cleaned Data
-	Pivot Tables
-	Dashboard 1
-	Dashboard 2

## Conclusion

The analysis highlights appointment lead time and patient age as important areas to consider when examining missed 
appointments. These findings can support further investigation into patient attendance patterns and strategies for improving
appointment management.


