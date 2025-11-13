📊 Supermarket Waiting Time Analysis
Statistical Research Project

This project investigates the waiting time in supermarket checkout lines in Israel, using real collected data and applying descriptive statistics, hypothesis testing, ANOVA, regression, and visual analysis.

The study examines how shift time, season, and store location influence the average waiting time of customers, and whether these differences are statistically significant.

🔍 Background & Motivation

Previous research indicates that customers often show low tolerance for being last in line, with a significantly higher probability of switching lines or abandoning their purchase altogether.
Despite this instinct, statistical findings show that switching lines usually makes the waiting time longer, sometimes by up to 67%.

Our project expands on this idea and analyzes real-world supermarket data to understand:

How long customers actually wait

What factors affect waiting time

Whether these factors are statistically significant

🎯 Project Objective

To analyze and model the waiting time at supermarket checkout lines in Israel and identify the main factors that influence waiting duration.

🧩 Variables
Dependent Variable

Waiting Time (minutes) – continuous variable

Independent Variables

Shift: Morning / Evening

Season: Summer / Winter

Store Location: North / Center / South

Cashier Age (used in regression model)

📈 Descriptive Statistics

Mean: 10.20

Median: 10.00

Mode: 8.50

Range: 18

Variance: 14.77

Standard Deviation: 3.84

The distribution is approximately normal, as confirmed by boxplot symmetry and bell-curve visualization.

🧪 Hypothesis Testing
1️⃣ Independent Samples Test – Shift (Morning vs Evening)

Result:
✔ Reject H₀
Morning shifts have a significantly higher mean waiting time than evening shifts (α = 0.05).

2️⃣ Paired Samples Test – Season (Summer vs Winter)

Result:
✔ Reject H₀
Waiting times in summer are significantly longer than in winter (α = 0.05).

🟦 One-Way ANOVA – Store Location

Comparing:

North

Center

South

Result:
✔ Significant difference found.
The Center stores have significantly lower waiting times compared to North/South (Duncan test).

🟪 Two-Way ANOVA – Shift × Location

Factors tested:

Shift (Morning / Evening)

Location (North / Center / South)

Assumptions verified:

Normality (Kolmogorov–Smirnov) ✔

Equal variances (Levene’s test) ✔

Results:

Shift: Not significant

Location: Significant

Shift × Location interaction: Significant

Conclusion:
Waiting time depends on store location and on the combination of location + shift.

📉 Linear Regression Analysis

Dependent Variable: Waiting Time
Independent Variable: Cashier Age

Model assumptions validated:
✔ Continuous variables
✔ No extreme outliers
✔ Linear relationship

📚 Files Included

Presentation: Supermarket_Waiting_Time_Analysis.pptx

Statistical graphs and outputs

Documentation & conclusions

✔ Summary

The project provides a full statistical analysis of real supermarket checkout data and shows:

Waiting times differ significantly by location

Morning is slower than evening

Summer is slower than winter

There is an interaction between shift and location

The data follows a roughly normal distribution

אם תרצי – אכין לך גם:
