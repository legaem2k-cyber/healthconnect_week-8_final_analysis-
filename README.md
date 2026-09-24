# healthconnect_week-8_final_analysis-
Final HealthConnect Data Analytics package — validated KPIs, Power BI dashboard, Excel analysis, business insights, recommendations, testing and final integration.
HealthConnect Week 8 — Final Data Analytics
Project Overview

HealthConnect Clinic Support Using Data and AI

The project explores how HealthConnect Clinic can use appointment data and AI to better understand missed appointments, support proactive follow-up, and improve appointment management.

Data Analytics Contribution

As part of the Data Analytics track, I analysed the HealthConnect appointment dataset and transformed the data into validated KPIs, visualisations, business insights and recommendations.

The analysis focused on identifying patterns associated with missed appointments and providing evidence to support decision-making.

Key Validated Findings
Overall no-show rate: 48.46%
2,423 of 5,000 appointments were recorded as no-shows.
No-show rates increased as booking lead time became longer.
No-show rate increased from 27.81% for appointments booked 0–7 days ahead to 60.49% for appointments booked 30–60 days ahead.
Previous no-show history was associated with higher subsequent no-show rates.
Appointments with a recorded reminder had a 47.36% no-show rate compared with 51.39% where no reminder was recorded.
Age groups showed relatively similar no-show rates and were not as strong an indicator as booking lead time and previous no-show history.
Week 7 Testing and Refinement

The Week 7 analysis was independently validated and refined.

Key validation activities included:

Checking Power BI KPI calculations against Excel calculations.
Testing dashboard interactions and filters.
Validating key age, reminder, lead-time and previous no-show results.
Adding caution around smaller groups.
Refining the interpretation of findings.
Confirming that the analysis identifies associations rather than causation.
Business Recommendations

Based on the analysis:

Monitor no-show KPIs using the Power BI dashboard.
Strengthen reminder and follow-up activity, particularly for appointments booked further in advance.
Use previous appointment behaviour as one factor when prioritising administrative follow-up.
Combine validated analytics findings with predictive modelling to support proactive appointment management.
Cross-Track Integration

The Data Analytics findings were prepared to support the wider HC-POD solution.

Data Analytics → Data Science

Validated findings helped inform the predictive modelling work.

Data Science → ML Engineering

The predictive approach can be prepared for technical integration into a usable workflow.

Generative AI

Supports administrative patient interactions using the approved HealthConnect Knowledge Base and defined safety boundaries.

Project Management

Coordinates dependencies, integration, readiness and final project delivery.

Important Technical Limitation

waiting_time_minutes should not be used as a predictive model input because it is recorded after the appointment process and can create data leakage.

The predictive approach should support human decision-making rather than make automatic decisions about patients.

Limitations
The analysis identifies associations, not causation.
Smaller groups should be interpreted cautiously.
Some fields contained missing values.
Further monitoring, testing and validation are required before predictive approaches are considered for operational deployment.
Evidence

The Week 8 work is supported by:

Excel analysis and calculations
Power BI dashboard
Testing and refinement evidence
Week 7 analysis documentation
Week 8 final analytics and decision-support documentation
Final presentation
Final presentation video stored in the Week 8 Google Drive folder
Final Takeaway

Data → Insights → Prediction → Action

HealthConnect can use appointment data and AI to support more proactive appointment management while maintaining appropriate human oversight.
