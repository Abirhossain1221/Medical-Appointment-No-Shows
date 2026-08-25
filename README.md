# Medical Appointment No Shows data analysis and visualization.
End-to-end data analytics project using PostgreSQL and Power BI

<img width="1600" height="640" alt="medical_noshow_banner_modern" src="https://github.com/user-attachments/assets/dab1a04c-7e67-4015-9e00-9d2f2428479c" />


Dataset  used :
For this EDA project I used 'Medical Appointment No Shows' from kaggle 
https://www.kaggle.com/datasets/joniarroba/noshowappointments/data

This CSV contains total of 111k rows and 14 coumumns here most of data is cleand except few errors wich I cleeandd in the first part of Postgres EDA.

Data inspection & cleaning
Rename handcap → disability_count
Remove age = -1
Calculate lead_time_days
Remove negative lead times
Exploratory Data Analysis
Overall no-show rate
Day-of-week analysis
Lead-time buckets
Age groups
SMS reminder analysis
Neighbourhood risk
Patient-level risk analysis
Previous appointments
Previous no-shows
Previous no-show rate
Window functions
Risk scoring view
v_appointment_risk
Risk tiers
High-risk patient identification

