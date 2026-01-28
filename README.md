Yulu Electric Bike Demand Analysis

Problem Statement :

Yulu, a leading micro-mobility service provider in India, observed a decline in revenue and wanted to understand what factors truly drive demand for shared electric cycles.
This project analyzes historical rental data to identify the impact of working days, weather, seasonality, and user behavior on bike rentals.

Dataset Overview :

Records: 10,886 hourly observations

Target Variable: count (total rentals)

Key Features:

Calendar: working day, holiday, season

Weather: temperature, feels-like temperature, humidity, windspeed

User type: casual vs registered

Approach & Methodology :

Exploratory Data Analysis (EDA)

Distribution analysis of rentals and weather variables

Categorical analysis for working days, seasons, and weather conditions

Statistical Analysis & Hypothesis Testing :

Normality testing: Shapiro–Wilk, Q–Q plots

Mean comparison: Two-sample t-test (working vs non-working days)

Multi-group comparison: ANOVA / Kruskal–Wallis (season & weather)

Association tests: Chi-Square tests (season vs weather, working day vs weather)

Correlation Analysis :

Pearson and Spearman correlations to quantify relationships between rentals, users, and weather variables

Key Insights :

Registered users are the strongest demand driver (correlation ≈ 0.97 with total rentals)

Working and non-working days show statistically significant differences in rental demand

Temperature and feels-like temperature positively influence demand, while humidity negatively impacts usage

Season and categorical weather labels alone do NOT significantly change average rentals

Casual users contribute to demand spikes, especially on favorable days

Business Recommendations :

Prioritize retention and subscription strategies for registered users

Use dynamic promotions to target casual users on non-working days and good weather

Allocate fleet based on short-term weather comfort metrics, not season alone

Differentiate marketing: commuter-focused (weekdays) vs leisure-focused (weekends)

Tools & Skills :

Python | Pandas | NumPy | EDA | Statistical Analysis | Hypothesis Testing (t-Test, ANOVA, Chi-Square) | CLT | Business Analytics
