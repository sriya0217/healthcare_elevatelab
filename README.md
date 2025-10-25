🩺 Project Overview — Healthcare Appointment No-Show Prediction

This project aims to predict whether a patient will miss their healthcare appointment (“No-Show”) using machine learning and visualize key insights with Power BI. The goal is to help hospitals and clinics optimize scheduling, reduce missed appointments, and improve patient care efficiency.

🔍 Problem Statement

Missed appointments lead to wasted resources, longer wait times, and reduced care efficiency. By predicting potential no-shows in advance, hospitals can take proactive actions such as sending extra reminders or rescheduling at-risk patients.

🎯 Objectives

Predict whether a patient will attend or miss their scheduled appointment.
Identify key factors influencing patient attendance (e.g., SMS reminders, age, chronic diseases, weekday).
Provide interactive insights through a Power BI dashboard.
Offer data-driven recommendations for optimizing appointment scheduling.

⚙️ Tools & Technologies

Python: Data cleaning, preprocessing, model training (Scikit-learn, Pandas, NumPy)
Power BI: Dashboard creation, KPI visualization, and trend analysis
Libraries Used: scikit-learn, pandas, matplotlib, seaborn, joblib

🧠 Machine Learning Model

Model Used: Decision Tree Classifier
Purpose: Classify patients into “Show” or “No-Show” categories

Key Features Considered:

Age, Gender
Days between scheduling and appointment
SMS reminders sent
Medical conditions (Diabetes, Hypertension, Alcoholism)
Scholarship/health aid
Appointment weekday

📊 Power BI Dashboard Insights

The Power BI dashboard provides a comprehensive visual analysis including:
KPIs: Total appointments, no-shows, scholarship count, chronic disease counts

Charts:

No-shows by gender and by day of the week
Age distribution of no-shows
Effectiveness of SMS reminders
Relationship between chronic diseases and attendance
Metrics Displayed:

Total Alcoholism: 3,360
Diabetes Cases: 7,943
Scholarships: 11K
SMS reminders: 35K
Trend Analysis: Shows how factors like age, weekday, and reminders affect attendance.

💡 Key Findings
SMS reminders ignificantly reduce no-shows.
Young and middle-aged patients have higher no-show rates than older adults.
Appointments scheduled far in advance are more likely to be missed.
Certain weekdays show higher no-show frequencies.
Patients with chronic diseases (especially diabetes) tend to attend more regularly.

🚀 Outcome

Built a predictive model to forecast no-shows with good accuracy.
Designed an interactive Power BI dashboard to monitor patient behavior and improve hospital scheduling.
Provided actionable recommendations to minimize no-shows using reminder strategies and optimized scheduling policies.
