Tools Used: PostgrSQL , Power BI

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

