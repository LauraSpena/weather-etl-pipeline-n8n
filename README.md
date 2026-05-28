# Weather ETL Pipeline with n8n

## Overview

This project demonstrates the development of an incremental ETL workflow using n8n to automate the ingestion of weather data from the Open-Meteo API.

The workflow retrieves historical meteorological information, transforms JSON responses into structured tabular records, validates existing data to prevent duplicates, and stores the results in Google Sheets for further Business Intelligence analysis.

---

## Workflow Architecture

```text
Manual Trigger
→ Open-Meteo API
→ Data Transformation
→ Historical Validation
→ Duplicate Filtering
→ Google Sheets
```

---

## Technologies

* n8n
* Open-Meteo API
* JavaScript
* Google Sheets

---

## Features

* API data ingestion
* JSON transformation
* Incremental loading logic
* Duplicate prevention
* Structured tabular output
* ETL workflow automation

---

## Output

The workflow generates a clean and structured weather dataset that can be connected to analytics and reporting tools such as Power BI.

---

## Repository Contents

* n8n workflow (.json)
* Workflow screenshots
* Example output dataset
* Project documentation

---

## Purpose

This repository was created as a portfolio project to demonstrate practical skills in API integration, ETL workflows, data transformation, and automation using n8n.
