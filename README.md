# COVID-19 Weekly Surveillance Analysis — Bangladesh

## Overview
This repository contains a descriptive weekly surveillance analysis of COVID-19 cases and deaths in Bangladesh. The project focuses on detecting epidemic waves and identifying abrupt week-to-week spikes using publicly available time-series data, following a Ministry of Health–style surveillance approach.

The analysis was conducted under mobile-only constraints and emphasizes practical surveillance logic rather than statistical modeling.

---

## Objectives
- Convert cumulative COVID-19 case and death data into weekly incident counts
- Generate weekly epidemic curves for cases and deaths
- Detect abrupt increases (spikes) in weekly transmission
- Interpret observed trends from a public health surveillance perspective

---

## Data Source
- Johns Hopkins University (JHU) COVID-19 global time-series dataset

---

## Methods
- Daily cumulative case and death counts were converted to daily incident data
- Daily data were aggregated into weekly totals
- Duplicate weekly entries were removed
- Weekly epidemic curves were plotted for cases and deaths
- Spike weeks were identified based on abrupt week-to-week increases
- Trends were interpreted descriptively without statistical modeling

---

## Key Findings
- Multiple distinct epidemic waves were observed across the surveillance period
- Several weeks showed abrupt spikes in reported COVID-19 cases
- Weekly deaths followed case trends with an approximate 1–3 week temporal lag
- Later epidemic waves showed higher case counts with relatively lower mortality compared to earlier waves

---

## Repository Contents
- **COVID19_Weekly_Surveillance_Bangladesh_Report.docx**  
  MOH-style surveillance mini-report with results, interpretation, and public health implications

- **p2_sheet.xlsx**  
  Working spreadsheet containing data processing steps and intermediate calculations

- **BD_COVID_weekly_cases_deaths.csv**  
  Final cleaned weekly dataset used for analysis

- **weekly_cases_epidemic_curve.png**  
  Weekly epidemic curve of confirmed COVID-19 cases

- **weekly_deaths_epidemic_curve.png**  
  Weekly epidemic curve of COVID-19 deaths

---

## Public Health Relevance
This project demonstrates applied disease surveillance skills, including data cleaning, weekly aggregation, spike detection, and epidemiological interpretation. The workflow and reporting style are aligned with national surveillance units, ICDDR,B, and WHO-type epidemic monitoring activities.

---

## Limitations
The analysis is based on aggregate publicly available data and may be affected by reporting delays, testing variability, and changes in surveillance practices over time. Findings are descriptive and should be interpreted as surveillance observations rather than causal inference.

---

## Disclaimer
This project is for educational and professional demonstration purposes only and does not represent official surveillance outputs of any public health authority.
