# Hi, I'm Emmanuel

**Business Analyst Intern at Fortress Real Estate Investments, moving into data engineering.**

At work I focus on feature enhancements to Fortress's internal application, gathering requirements and leading user acceptance testing for current and upcoming features. I also work on automating the budget process and key Power BI reports. In my own projects I build the pipelines behind that kind of reporting: ingestion, validation, modelling and the checks that keep the data reliable.

**[Portfolio](https://emmanuel-esplin.github.io)** · **[Printable CV](https://emmanuel-esplin.github.io/cv)**

## Current Focus

- Orchestrating and testing batch pipelines with **Airflow**, **dbt** and **Great Expectations**
- Designing layered data models (staging → core → mart) in **DuckDB**, **MySQL** and **PostgreSQL**
- Automating API tests with **Playwright** and **TypeScript**
- Learning **AWS** cloud services and **Databricks**

## Featured Projects

### [nyc-taxi-pipeline](https://github.com/Emmanuel-Esplin/nyc-taxi-pipeline)

An end-to-end batch pipeline that takes 11.2M NYC taxi records from raw files to a Metabase dashboard. Reruns are idempotent per month, rejected rows are quarantined with their reasons, and row counts are reconciled between stages. It runs from one `docker-compose.yml`, with CI on every pull request.

**Stack:** Airflow, dbt, DuckDB, Great Expectations, Postgres, Metabase, Docker, GitHub Actions

### More projects

| Project | Description | Stack |
| --- | --- | --- |
| [portfolio-api-tests](https://github.com/Emmanuel-Esplin/portfolio-api-tests) | API tests for my portfolio site and the GitHub REST API, with a bounded self-heal layer that records every retry and a nightly strict run | Playwright, TypeScript, zod |
| [SQL-Projects](https://github.com/Emmanuel-Esplin/SQL-Projects) | Diamond Tracker, a web app on a MySQL database with procedures, triggers and views, plus a general ledger model and SQL exercises | MySQL, FastAPI, PostgreSQL |
| [de-cookbook-practice](https://github.com/Emmanuel-Esplin/de-cookbook-practice) | Spark recipes worked through from Packt's *Data Engineering with Databricks Cookbook*, organised as Gradle modules with tests and CI | PySpark, Delta Lake, Gradle |
| [Python_Projects](https://github.com/Emmanuel-Esplin/Python_Projects) | Data analysis, statistics and machine learning scripts, plus automation utilities | pandas, scikit-learn, XGBoost |
| [Data_Science_Fundamentals](https://github.com/Emmanuel-Esplin/Data_Science_Fundamentals) | Reproducible notebooks on NumPy, pandas and introductory machine learning, run by CI | Jupyter, pandas, scikit-learn |
| [R_Projects](https://github.com/Emmanuel-Esplin/R_Projects) | Statistical analysis, visualisation and introductory machine learning | R |

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**Data Engineering**

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6310?style=flat)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-003366?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Databases**

![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Tools & Platforms**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat&logo=metabase&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)

## Connect

I'm open to junior data engineering, data analyst and BI roles. See my [portfolio](https://emmanuel-esplin.github.io), or open an issue on any of my projects.
