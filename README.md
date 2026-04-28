# Databricks Data Pipeline Project

## Overview
End-to-end data pipeline built with PySpark and Delta Lake
on Databricks, following Medallion architecture.

## Pipelines
- Level 1: CSV ingestion → Delta table (PySpark, manual schema)
- Level 2: Bronze → Silver → Gold (Medallion architecture)
- Level 3: Auto Loader, Delta Live Tables, Workflows

## Tech stack
Databricks · PySpark · Delta Lake · Python · SQL

## How to run
1. Import notebooks into a Databricks Repo
2. Attach to a cluster (DBR 13+)
3. Run notebooks top to bottom
