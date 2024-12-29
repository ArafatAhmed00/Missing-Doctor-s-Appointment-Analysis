Medical Appointments No-Show Analysis
Project Overview

This project focuses on analyzing a dataset containing records of medical appointments in Brazil. The primary objective is to identify factors influencing whether a patient shows up for their appointment. The dataset includes information on 110,527 medical appointments with 14 associated variables, such as patient demographics, health conditions, and communication methods.
Dataset Description

Source: The dataset was sourced from Kaggle and contains comprehensive details about each appointment, including patient background information.
Key Columns:

    PatientId: Unique identifier for each patient (not relevant to analysis).
    AppointmentID: Unique identifier for each appointment (not relevant to analysis).
    Gender: Indicates if the patient is male or female.
    Scheduled Day: The date the appointment was scheduled.
    Appointment Day: The date of the actual appointment.
    Age: Patient's age in years.
    Neighborhood: The location of the medical facility.
    Scholarship: Indicates participation in Bolsa Familia, a Brazilian social welfare program.
    Hypertension: Indicates if the patient has hypertension.
    Diabetes: Indicates if the patient has diabetes.
    Alcoholism: Indicates if the patient has alcoholism.
    Handicap: Indicates if the patient has any physical handicap.
    SMS_received: Indicates if the patient received SMS notifications.
    No-show: Indicates whether the patient attended the appointment.

Objective

The primary goal of the project is to uncover insights into the factors affecting no-shows at medical appointments. Specifically:

    Determine the correlation between patient characteristics and appointment attendance.
    Identify actionable insights for improving appointment adherence rates.

Methodology
1. Data Profiling and Preparation

    Ensured high data quality with no missing values or irrelevant columns.
    Performed transformations and outlier handling to prepare the dataset for analysis.
    Focused on key variables like SMS_received, AwaitingTime, ScheduledDay_month, and ScheduledDay_week.

2. Data Visualization

    Visualized correlations between variables using heatmaps and scatter plots.
    Highlighted the impact of key features on the no-show behavior.

3. Predictive Modeling

    Employed machine learning models to predict no-show probabilities based on patient and appointment features.
    Evaluated models for accuracy and reliability.

Key Findings

    Patients who did not receive SMS notifications were more likely to miss appointments.
    Longer awaiting times between scheduling and appointment dates increased the likelihood of no-shows.
    Certain neighborhoods exhibited higher no-show rates, suggesting possible accessibility issues.

Conclusion

This analysis provides valuable insights into patient behaviors and actionable recommendations for healthcare providers to improve appointment adherence rates.
