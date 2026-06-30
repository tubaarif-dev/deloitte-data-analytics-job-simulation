# Deloitte Australia Data Analytics Job Simulation

> Data analytics case study completed as part of the Deloitte Australia Data Analytics Job Simulation on Forage using Tableau and Microsoft Excel.

---

## Table of Contents

- [Overview](#overview)
- [Business Scenario](#business-scenario)
- [Project Objectives](#project-objectives)
- [Tools & Technologies](#tools--technologies)
- [Task 1: Factory Telemetry Analysis](#task-1-factory-telemetry-analysis)
- [Task 2: Employee Equality Score Classification](#task-2-employee-equality-score-classification)
- [Key Results](#key-results)
- [Skills Demonstrated](#skills-demonstrated)
- [Repository Structure](#repository-structure)
- [Screenshots](#screenshots)
- [Certificate](#certificate)
- [Project Files](#project-files)
- [What I Learned](#what-i-learned)
- [Acknowledgements](#acknowledgements)

---

## Overview

This repository documents my completed work for the **Deloitte Australia Data Analytics Job Simulation** on **Forage**.

The simulation provided hands-on experience with realistic business scenarios inspired by the type of work performed by Deloitte Australia's Data Analytics and Forensic Technology teams.

Across two practical tasks, I analyzed operational and workforce data using industry-standard tools to answer business questions, build interactive visualizations, and classify employee equality scores based on defined business rules.

Through this project, I strengthened my skills in data analysis, business problem solving, dashboard development, spreadsheet automation, and communicating insights through data.

---

## Business Scenario

Daikibo Industrials partnered with Deloitte Australia to analyze operational and employee data in support of two business initiatives.

The first initiative focused on manufacturing performance. Using telemetry data collected from four factories, the goal was to identify which locations experienced the highest machine downtime and determine which equipment types contributed most to operational disruptions.

The second initiative focused on workforce equality. Employee compensation data had already been processed into equality scores, and the objective was to classify those scores into meaningful categories that could support reporting and further investigation.

These scenarios reflect how data analytics helps organizations improve operational efficiency and support informed business decisions.

---

## Project Objectives

- Analyze factory telemetry data to identify operational downtime.
- Build an interactive Tableau dashboard.
- Compare downtime across manufacturing locations.
- Identify the machine types responsible for the highest downtime.
- Classify employee equality scores using Microsoft Excel.
- Apply business rules to automate data classification.
- Present findings in a clear and structured format.

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Tableau Public | Interactive dashboard creation |
| Microsoft Excel | Data analysis and classification |
| JSON | Factory telemetry dataset |
| GitHub | Project documentation and version control |
| Markdown | Repository documentation |

---

## Task 1: Factory Telemetry Analysis

### Background

Daikibo Industrials collected one month of telemetry data from four manufacturing facilities located in:

- Tokyo, Japan
- Osaka, Japan
- Berlin, Germany
- Shenzhen, China

Each factory operated multiple machine types that transmitted operational data every ten minutes throughout May 2021.

The objective was to identify where machine downtime occurred most frequently and determine which equipment contributed most to those issues.

### Business Questions

The analysis focused on answering two questions:

1. Which factory experienced the highest machine downtime?
2. Which machine types contributed most to downtime in that factory?

### Dataset

The telemetry dataset included information such as:

- Factory
- City
- Country
- Device Type
- Device ID
- Area
- Section
- Temperature
- Timestamp
- Machine Status

A calculated measure named **Unhealthy** was created in Tableau to represent ten minutes of downtime whenever a machine reported an unhealthy status.

### Methodology

The workflow included:

- Importing the JSON dataset into Tableau.
- Creating a calculated field named **Unhealthy**.
- Building a bar chart showing downtime by factory.
- Creating a second bar chart showing downtime by device type.
- Combining both charts into an interactive dashboard.
- Configuring the factory chart as a dashboard filter.
- Using the dashboard to identify the machines responsible for downtime within the selected factory.

### Dashboard

The Tableau dashboard visualizes machine downtime across Daikibo's manufacturing facilities. Users can compare downtime by factory and interactively filter the results to identify which machine types contributed most to downtime at the selected location.

### Key Findings

The analysis showed that:

- **Daikibo Factory Seiko** recorded the highest machine downtime.
- **Daikibo Shenzhen** also experienced significant downtime.
- **LaserWelder** and **LaserCutter** were the machine types responsible for the greatest amount of downtime.
- **Berlin** recorded the lowest downtime among all factory locations.

These findings help identify where maintenance efforts and operational improvements should be prioritized.

---

## Task 2: Employee Equality Score Classification

### Background

Daikibo Industrials also requested support in reviewing employee equality scores generated by Deloitte's Forensic Technology team.

Each employee role had already been assigned an Equality Score ranging from **-100 to +100**, where **0 represented ideal equality**.

The objective was to classify each score according to predefined business rules.

### Classification Rules

| Equality Score | Classification |
|---------------|----------------|
| -10 to 10 | Fair |
| -20 to -11 and 11 to 20 | Unfair |
| Less than -20 or greater than 20 | Highly Discriminative |

### Excel Solution

A formula was used to automatically classify every equality score into its appropriate category based on the provided business rules.

This ensured consistent classification across the dataset while reducing manual effort.

### Outcome

The completed worksheet successfully classified all employee equality scores into their respective categories, supporting future reporting and analysis of potential pay inequality across different factories and job roles.

---

## Key Results

- Created an interactive Tableau dashboard for operational analysis.
- Identified the manufacturing location with the highest downtime.
- Determined the machine types contributing most to equipment failures.
- Classified employee equality scores using Excel.
- Applied business rules to automate data categorization.
- Produced clear visual and spreadsheet-based insights for decision-making.

---

## Skills Demonstrated

- Data Analysis
- Data Visualization
- Dashboard Development
- Tableau Public
- Microsoft Excel
- Business Analysis
- Data Interpretation
- Spreadsheet Automation
- Problem Solving
- Analytical Thinking
- Data Storytelling

---

## Repository Structure

```text
deloitte-data-analytics-job-simulation/
│
├── README.md
├── LICENSE
├── Dashboard - task 1.png
├── Task 5 Equality Table.xlsx
├── Deloitte Australia Data Analytics Job Simulation on Forage.pdf
└── Certification of Deloitte Australia Data Analytics on Forage.png
```

---

## Screenshots

### Factory Downtime Dashboard

The Tableau dashboard compares machine downtime across Daikibo's manufacturing facilities and allows interactive filtering to identify the machine types contributing most to downtime.

![Factory Downtime Dashboard](Dashboard%20-%20task%201.png)

---

## Certificate

I successfully completed the **Deloitte Australia Data Analytics Job Simulation** on **Forage**.

### View Certificate

[View the Deloitte Australia Data Analytics Job Simulation Certificate (PDF)](Deloitte%20Australia%20Data%20Analytics%20Job%20Simulation%20on%20Forage.pdf)

### Certificate Preview

![Deloitte Certificate](Certification%20of%20Deloitte%20Australia%20Data%20Analytics%20on%20Forage.png)

---

## Project Files

This repository includes the following project files:

- **Dashboard - task 1.png** – Interactive Tableau dashboard showing downtime analysis.
- **Task 5 Equality Table.xlsx** – Completed Excel worksheet with equality score classifications.
- **Deloitte Australia Data Analytics Job Simulation on Forage.pdf** – Completion certificate.
- **Certification of Deloitte Australia Data Analytics on Forage.png** – Certificate preview image.

---

## What I Learned

This simulation gave me practical experience working with business datasets and reinforced the importance of turning raw data into actionable insights.

I improved my ability to build interactive dashboards, interpret operational data, and communicate findings in a clear and meaningful way. I also strengthened my Excel skills by applying business rules to automate data classification and support decision-making.

Most importantly, the project highlighted how data analytics can be used to solve real business problems, from improving manufacturing performance to supporting workplace equality initiatives.

---

## Acknowledgements

This project was completed as part of the **Deloitte Australia Data Analytics Job Simulation** offered by **Forage**.

The simulation provided valuable hands-on experience with realistic analytics tasks inspired by Deloitte's consulting work.

The analyses, dashboard, documentation, and repository presented here reflect my own work completed during the simulation.
