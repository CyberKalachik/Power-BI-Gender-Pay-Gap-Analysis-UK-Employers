# Power-BI-Gender-Pay-Gap-Analysis-UK-Employers
This project presents an interactive Power BI report analyzing the Gender Pay Gap across UK employers, complemented by a detailed company-level case study of Lincoln City Football Club. 

## 📊 Gender Pay Gap Analysis — UK Employers

📌 Project Overview

This project presents an interactive Power BI report analyzing the Gender Pay Gap across UK employers, complemented by a detailed company-level case study of Lincoln City Football Club.

**The analysis explores how gender pay inequality varies across:**

-Employer sectors
-Employer sizes
-Pay quartiles
-Bonus eligibility

The report demonstrates that extreme gender pay gaps are often structural, driven by workforce composition and access to bonuses rather than unequal pay for the same roles.

## 📄 Report Structure

## 1. Executive Overview

An aggregated, high-level view of gender pay inequality across UK employers.

Key indicators:

Distribution of Median Gender Hourly Pay Gap

Mean vs Median Gender Pay Gap (%)

Women in Top Pay Quartile (%)

Bonus eligibility by gender

Interactive features:

Sector selection (based on UK SIC codes)

Employer size filtering

Dynamic insights panel

## 2. Sector-Level Analysis

This section enables comparison across industries to highlight structural differences in gender pay outcomes.

Includes:

Median Gender Pay Gap by Sector (%)

Sector-level distributions of hourly pay gaps

Identification of sectors with significant over- or under-representation of women in top pay quartiles

## 3. Company Case Study — Lincoln City Football Club

A focused company-level analysis illustrating how extreme gender pay and bonus gaps can emerge.

Key analyses:

Gender distribution across pay quartiles

Comparison with UK averages

Bonus eligibility gaps (Company vs UK)

Interactive insight panel explaining key drivers of inequality

🧮 Data Model & DAX Measures

The report relies on a custom set of DAX measures, including:

Mean Gender Pay Gap (Company & UK Average)

Median Gender Pay Gap (Company & UK Average)

Women in Top Pay Quartile (%)

Mean Bonus Pay Gap (%)

Bonus Eligibility by Gender (Company & UK Average)

Bonus Eligibility Gap (percentage points)

Employer count for aggregated analysis

Dynamic Cover Value measure used to populate the executive summary matrix

A UK SIC codes catalogue was integrated into the model and adapted using DAX to enable sector-based filtering and analysis.

📂 Data Source

UK Government Gender Pay Gap Service
Reporting year: 2025–2026
https://gender-pay-gap.service.gov.uk/viewing/download

🛠 Tools & Technologies

Power BI

DAX

UK SIC Classification

OBS Studio (report walkthrough recording)

🎯 Key Takeaways

Gender pay gaps are primarily structural, not purely wage-based

Under-representation of women in top pay quartiles is a major driver of inequality

Bonus pay gaps often reflect access to bonuses, not differences in bonus size

Company-level patterns can deviate significantly from national averages
