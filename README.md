Bellabeat Leaf — Smart Device Usage Analysis

Google Data Analytics Certificate | Capstone Case Study
Tools: Python · pandas · matplotlib · seaborn · Tableau
Dataset: FitBit Fitness Tracker Data (Kaggle/Möbius, CC0)


Project Summary
Analyzed FitBit smart device usage data from 35 users across two time periods (March–May 2016) to identify behavioral trends in daily activity, sleep, and sedentary patterns. Applied those insights to Bellabeat's Leaf wellness tracker to produce three data-driven marketing recommendations.

Key findings:
_Users spend 80.6% of their day sedentary (avg 990 min/day)
_Average daily steps are 7,328 — 27% below the CDC 10,000-step target
_Only 20% of users (7 of 35) consistently hit 10,000 steps/day
_Users average 39 minutes awake in bed per night despite 7 hrs sleep
_Saturday is the most active day, Sunday the least active
_Peak activity windows occur at 12–1pm and 5–7pm daily


Tableau Dashboard
🔗 View the interactive dashboard on Tableau Public
Link will be updated after publishing

Repository Structure
 bellabeat-case-study/
 │
 ├── README.md
 ├── notebooks/
 │   ├── bellabeat_leaf_analysis.ipynb
 │   └── bellabeat_cleaning.ipynb
 ├── visuals/
 │   ├── 00_summary_dashboard.png
 │   ├── 01_activity_by_day.png
 │   ├── 02_hourly_activity.png
 │   ├── 03_sleep_quality.png
 │   ├── 04_sedentary_behavior.png
 │   ├── 05_user_segments.png
 │   └── 06_activity_vs_sleep.png
 └── tableau_exports/
     ├── daily_activity_clean.csv
     ├── steps_by_weekday.csv
     ├── hourly_averages.csv
     ├── sleep_clean.csv
     ├── user_segments.csv
     └── activity_vs_sleep.csv

Key Findings
# Finding                                            Leaf Implication1Saturday 
1 most active, Sunday least (1,190 step gap)         Target Sunday and Friday for app challenges
2 Activity peaks at 12–1pm and 5–7pm daily           Schedule reminders at 10:30am and 4pm
3 39 min awake in bed per night on average           Campaign on sleep quality gap
4 80.6% of day spent sedentary                       Market Leaf's inactivity alerts as hero feature
5 52% of users are Sedentary or Low Active           Target aspirational moderate exercisers
6 Weak correlation between steps and sleep duration  Focus on holistic tracking story

The 3 Leaf Marketing Recommendations
1. Position Leaf as the antidote to invisible inactivity
Users spend 80.6% of their day sedentary without realising it.
Campaign angle: "You sat for 3 hours without noticing. Leaf noticed."
2. Time Leaf notifications around users' natural activity peaks
Pre-peak reminders at 10:30am and 4pm amplify existing habits.
Campaign angle: "Leaf works with your rhythm, not against it."
3. Lead with sleep quality, not just sleep duration
Users spend 39 min awake in bed despite adequate hours in bed.
Campaign angle: "8 hours in bed doesn't mean 8 hours of rest. Leaf shows you the difference."

Data Sources
Dataset                      Period       Users    Source
FitBit Fitness Tracker Data  Mar–Apr2016  35       Kaggle/Möbius CC0 
FitBit Fitness Tracker Data  Apr–May2016  35       Kaggle/Möbius CC0

Data Limitations

35 users — too small for statistical significance
Data collected in 2016 — usage patterns have evolved
No demographic data — gender, age, location unconfirmed
Weight log covers only 13 users — excluded from main analysis
Sleep data only available for 24 of 35 users


How to Reproduce

1. Open notebooks/bellabeat_leaf_analysis.ipynb in Google Colab
2. Mount Google Drive and point BASE path to your data folder
3. Run all cells in order
4. Charts save automatically to visuals/
5. Tableau exports save automatically to tableau_exports/


Tools Used
Tool                     Purpose
Python (pandas, numpy)   Data cleaning and analysis
matplotlib, seaborn      Data visualization
Google Colab             Development environment
Google Drive             File storage
Tableau Public           Interactive dashboard
GitHub                   Version control and portfolio

Completed as part of the Google Data Analytics Professional Certificate.
