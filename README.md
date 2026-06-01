# Financial KPI Reporting

Monthly finance reporting project focused on actuals, budget variance, margin, and executive KPIs.

## Business Questions

- Where are actuals above or below budget?
- Which units contribute most to profit?
- Which expense lines need attention?
- What should the CFO see first?

## Repository Structure

```text
data/                 Sample data for the case study
src/                  Python analysis workflow
sql/                  SQL queries for KPI extraction
reports/              Executive summary and recommendations
outputs/              Generated analysis outputs, ignored by git
requirements.txt      Python dependencies
```

## How To Run

```bash
pip install -r requirements.txt
python src/analysis.py
```

The script reads `data/sample_data.csv`, creates KPI summaries, and saves generated outputs in `outputs/`.

## Analyst Skills Demonstrated

- Cleaning and profiling a structured dataset
- Creating KPI summaries with Python
- Writing SQL-style business questions
- Translating metrics into executive recommendations
- Organizing a reproducible portfolio repository
