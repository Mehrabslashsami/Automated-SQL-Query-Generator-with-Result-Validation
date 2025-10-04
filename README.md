# SQL Query Validation Project

This project is a small Python setup to create a sample company database and check SQL queries against expected results. It’s easy to run in Google Colab or locally.

## What It Does

- Creates a SQLite database (`company.db`) with:
  - `departments` table
  - `employees` table
- Runs a set of SQL queries and checks:
  - If they run without errors
  - If they return the expected number of rows
  - Shows a few sample results for quick inspection
- Generates a JSON report (`sql_validation_report.json`) summarizing everything

## Files

- `validator_colab.py` — Main script (creates DB, runs queries, validates, saves report)
- `README.md` — This file
- `sql_validation_report.json` — Example report (optional)

## How to Use

1. Clone the repo:

```bash
git clone <repo-url>
cd <repo-folder>
