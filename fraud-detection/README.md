# Credit Card Fraud Detection

## Problem
Identify fraudulent credit card transactions from 284,807 
European cardholder transactions (September 2013).

## Pipeline
| Layer | What it does |
|---|---|
| Bronze | Raw CSV ingested as Delta table |
| Silver | Typed, cleaned, time + amount buckets added |
| Gold | Feature engineered, model-ready |
| Predictions | Scored with Gradient Boosted Trees |

## Key Findings
- Fraud concentrates in micro (<€10) transactions — 249 cases
- Large transactions (>€1000) disproportionately safe — only 9 fraud cases
- Model AUC-ROC: [paste your score here]

## Tools
Databricks Community Edition · PySpark · Delta Lake · Tableau Public

## Dashboard
[View on Tableau Public →](paste your tableau link here)
