# School District Fleet Maintenance and Operational Optimizer
Project Overview
School districts and local governments face the constant challenge of maintaining large vehicle fleets and infrastructure on limited budgets. This project develops a Predictive Maintenance Engine designed to transition fleet management from costly reactive repairs to data-driven proactive maintenance.

By predicting the Remaining Useful Life (RUL) of school bus engines based on telematics data (mileage, idle time, and thermal stress), this tool allows districts to schedule repairs during planned downtime, ensuring student transport remains uninterrupted while maximizing taxpayer dollars.


-------------------------------------------------------------------------------------------------------------------------------
Operational Data Engineering
In the public sector, context is everything. This project simulates and analyzes Telematics Logs with a focus on specific school district Key Performance Indicators (KPIs):

Idle Time Monitoring: Tracking excessive idling during student loading zones, a primary driver of engine wear and fuel waste.

Thermal Stress Tracking: Identifying consistent high-heat operations that signal cooling system degradation.

Rolling Trend Analysis: Engineered 7-day moving averages to differentiate between one-off environmental spikes and genuine mechanical failure patterns.
----------------------------------------------------------------------------------------------------------------------------
Modeling and Fiscal Impact
I utilized XGBoost Regression to predict the specific number of days until a maintenance event is required.

Predictive Accuracy
The model achieved a Mean Absolute Error (MAE) of1.6567074060440063 days, providing garage managers with a reliable window for scheduling inspections.

The ROI Calculator (Budget Impact)
To demonstrate the value of this AI to district stakeholders, the project includes a cost-benefit analysis comparing two maintenance strategies:

Reactive Maintenance: Estimated at $5,000 per event (Includes emergency towing, student transit delays, and rush-order parts).

Predictive Maintenance: Estimated at $1,200 per event (Includes scheduled labor and preventative part replacement).
----------------------------------------------------------------------------------------------------------------------------
Results and Public Sector Benefits
Fiscal Responsibility: Shifted the majority of repairs to the low-cost predictive category, resulting in significant budgetary relief.

Student Safety: Reduced the risk of on-route vehicle breakdowns, ensuring a more reliable transportation experience for the student population.

Operational Transparency: Provides a "Fleet Health Monitor" that allows administrators to allocate limited mechanic resources to the highest-risk vehicles first.
----------------------------------------------------------------------------------------------------------------------------
Technical Stack
Language: Python (Google Colab)

Modeling: XGBoost Regressor

Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn
----------------------------------------------------------------------------------------------------------------------------
Author: Dhruv Shekar 
Focus: Public Sector Efficiency

