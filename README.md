# Suspicious Login Attempts — Cybersecurity Analysis Demo

[![GitHub last commit](https://img.shields.io/github/last-commit/Wil421-hu/suspicious-login-analysis)](https://github.com/Wil421-hu/suspicious-login-analysis)
[![RMarkdown](https://img.shields.io/badge/RMarkdown-Analysis-blue)](suspicious_login_analysis.Rmd)
[![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange)](https://public.tableau.com/app/profile/wil.jero/viz/SuspiciousLoginAttempts/Dashboard1)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Project Overview
This project demonstrates **cybersecurity incident analysis** using **SQL**, **RMarkdown**, and **Tableau** to investigate suspicious login attempts from an attack actor.  
The workflow focuses on **geolocation mismatch detection** — identifying login events where the country of access does not match the employee's office location.

## Objectives
- Detect **suspicious login attempts** based on location mismatch.
- Count **failed logins** by country to spot unusual access patterns.
- Visualize login trends with **Tableau dashboards**.
- Demonstrate integration of SQL queries with RMarkdown for reporting.

## Project Structure
- Project_cybersecurity_Demo.Rmd # Main RMarkdown analysis file
- output_report.pdf # Final PDF report (generated from RMarkdown)
- /images # Supporting visuals and screenshots
- README.md # Project documentation

## Tools & Technologies
- **SQL** — Data querying and conditional logic for location mismatch detection.
- **RMarkdown** — Reproducible analysis & PDF/HTML reporting.
- **Tableau** — Interactive visualizations & dashboards.
- **GitHub** — Version control and project sharing.

## Key Insights
- Login attempts from **unexpected countries** were flagged for review.
- Certain regions showed **multiple failed logins**, suggesting targeted access attempts.
- Visual trends helped pinpoint **time-based spikes** in suspicious activity.

## Sample Output
![Suspicious Login Dashboard](map_country_office.png)

## How to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/Wil421-hu/suspicious-login-analysis.git
2. Open Project_cybersecurity_Demo.Rmd in RStudio.
3. Knit the document to PDF or HTML.
4. Explore the Tableau dashboard for interactive filtering.

## Interactive Dashboard
View the live Tableau visualization here:
👉  https://public.tableau.com/app/profile/wil.jero/viz/SuspiciousLoginAttempts/Dashboard1

##  Topics / Tags
cybersecurity sql rmarkdown tableau data-analysis security-analytics

##  License
This project is licensed under the MIT License — see the file for details.
👉  ![LICENSE](LICENSE)

Author: Wil Njeru

Cybersecurity & Data Analytics Professional.
