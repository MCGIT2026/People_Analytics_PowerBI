# People Analytics — HR Attrition & Workforce Happiness
<img width="1291" height="726" alt="overview" src="https://github.com/user-attachments/assets/5695f22f-a89d-4ab1-b0dc-6c3c566b59c8" />
<img width="1291" height="720" alt="attrition-risks" src="https://github.com/user-attachments/assets/5750e23a-8197-4fec-a884-c72dc1768bf1" />
<img width="1293" height="719" alt="risk-detail" src="https://github.com/user-attachments/assets/33bacad9-756c-4290-86b0-80d50f95e86a" />
<img width="1291" height="722" alt="happiness" src="https://github.com/user-attachments/assets/cd910bfb-e742-4ba7-8941-b2dfd2f60187" />


**Power BI | People Analytics | HR Data Modelling | DAX | Power Query**

An interactive HR analytics project developed as part of the CEGID Data Analytics training programme, within the Power BI module.

The project simulates a business scenario in which a newly appointed HR manager needs to understand the organisation, investigate employee attrition and assess workforce happiness. 
The solution brings together multiple data sources, a structured data model and interactive dashboards to support data-driven HR exploration.

## Business Objectives
The project was built around three main business objectives.

### 1. Company Overview — Understanding the Organisation
Provide a newly appointed HR manager with a comprehensive overview of the organisation and its workforce.
The dashboard enables exploration of employee distribution and workforce characteristics across relevant organisational and demographic dimensions.

### 2. Employee Attrition — Understanding Exits and Exploring Risk Profiles
Investigate employee departures to identify patterns and characteristics associated with attrition.
The analysis goes beyond counting exits by exploring employee segments and characteristics that may be associated with a higher likelihood of leaving.
A key component is the development of an **attrition persona**: a representative profile derived from characteristics observed among employees who left the organisation. The persona helps HR explore recurring patterns and identify segments that may deserve further investigation.
The dashboard also supports the exploration of risk indicators and employee profiles, providing a foundation for more proactive retention analysis.

### 3. Workforce Happiness — Survey Analysis and Office Intervention
Explore employee happiness and satisfaction using two employee surveys conducted at different points in time.
The analysis also investigates whether changes in employee experience were observed following the introduction of an office desk-related initiative before the second survey.
Relevant indicators include happiness, job satisfaction, environment satisfaction, job involvement and work-life balance, subject to the fields available in the survey data.


## Analytical Design — One Dashboard, Multiple Questions
A central design principle was to maximise the analytical value of the available data while allowing users to investigate multiple business questions in the same reporting environment.
Rather than requiring separate reports for every question, the dashboard uses interactive filters, slicers and cross-filtering to explore several dimensions together.
The objective is to make the dashboard flexible and useful for exploratory HR analysis, while keeping the reporting experience coherent and accessible.

## Dashboard Pages
The report is organised around the following analytical areas, depending on the pages available in the final Power BI file:

- **Company Overview** — workforce composition and key HR indicators.
- **Organisational Happiness** — survey-based happiness, satisfaction and employee experience.
- **Attrition & Risk Profiles** — employee departures, attrition patterns and representative profiles.
- **Risk Analysis** — detailed exploration of the risk indicators and segments implemented in the report.

## Data & Methodology
The project follows a structured analytics workflow:

1. **Business understanding** — translate the three business objectives into analytical questions.
2. **Data understanding** — examine source datasets, fields, structure and limitations.
3. **Data preparation** — clean, transform and organise data using Power Query.
4. **Data modelling** — structure the data using fact and dimension tables and define relationships.
5. **Measures and KPIs** — implement analytical calculations using DAX.
6. **Visualisation** — develop interactive reports, filters and cross-filtering behaviour.
7. **Interpretation** — use the resulting views to explore patterns and support HR-oriented discussions.

## Tools & Technologies
- **Microsoft Power BI** — interactive dashboards and reporting.
- **Power Query (M)** — data ingestion and transformation.
- **DAX** — measures, KPIs and analytical calculations.
- **Excel and CSV** — source datasets and supporting files.
- **GitHub** — version control, documentation and portfolio presentation.

## Repository Contents
- `data/` — source datasets and supporting data files.
- `data_preparation/` — data preparation and transformation artefacts.
- `power-bi/` — Power BI report (`.pbix`).
- `README.md` — project overview, objectives and methodology.

## How to Use
1. Download or clone this repository.
2. Open the Power BI report located in `power-bi/` using Power BI Desktop.
3. If prompted, verify the data source configuration and ensure the required files are accessible.
4. Use the report navigation, slicers and cross-filtering to explore the available analysis.

The report may rely on source URLs or paths configured in Power Query. If these sources change, the queries may need to be updated.

## Project Context & Contribution
This project was developed as part of a training project. This repository is an individual portfolio copy intended to document the project artefacts and demonstrate the analytical workflow.
The portfolio presentation focuses on the business questions, data preparation, data modelling and reporting approach applied in the project.

## Privacy, Limitations & Responsible Use
This is an educational project based on the datasets available for the exercise. Its conclusions are limited by the quality, scope and structure of those datasets.
Attrition patterns and risk-oriented profiles should be used to guide further analysis, not to label individual employees or make employment decisions. Survey comparisons should be interpreted carefully, particularly when assessing the possible impact of an intervention without a controlled evaluation design.
The report is intended for learning and analytical demonstration, not as a production HR decision system.


