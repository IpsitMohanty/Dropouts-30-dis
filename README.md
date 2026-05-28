# Dropouts 30 Districts

Notebook-based analysis of **dropout records across 30 districts**, focused on district-wise comparisons, student-status patterns, and year-over-year dropout summaries.

This repository is an education-data analysis notebook built around a local Excel workbook rather than a packaged software project.

## What This Project Does

The notebook loads dropout data from a multi-sheet Excel file and performs exploratory analysis over district-level records.

Current analysis includes:

- loading and inspecting dropout records from an Excel workbook
- district-wise dropout counts
- record-level inspection of student and status fields
- cumulative dropout summaries across academic years
- chart-based reporting over district and year-level patterns

## Why It Exists

Dropout data often arrives as administrative spreadsheets that are difficult to summarize consistently.

This notebook helps convert that raw workbook into a clearer view of:

- which districts contribute the largest dropout counts
- how dropout records are distributed across the dataset
- how cumulative dropout totals evolve across academic years

## Repository Structure

- `Dropouts 30 dis..ipynb`
  Main notebook containing the exploratory analysis and visual reporting workflow.

## Data Notes

The notebook expects a local Excel file path from the author’s environment and uses source data that is not committed to the repository.

To rerun it, a user will typically need to:

- provide the relevant dropout workbook locally
- update the file path inside the notebook
- regenerate any charts or derived outputs

## Running the Notebook

Typical local setup:

```bash
pip install pandas matplotlib openpyxl jupyter
jupyter notebook
```

Then open:

- `Dropouts 30 dis..ipynb`

## Current Scope

This repository is exploratory and notebook-first.

It does not currently include:

- a reusable analysis package
- pinned environment files
- automated report generation scripts
- committed input data for immediate execution

## Suggested Next Improvements

- rename the notebook file to something cleaner and more stable
- document the workbook schema and expected sheets
- add exported visuals to the README
- refactor the analysis into reusable scripts if this becomes a recurring workflow
