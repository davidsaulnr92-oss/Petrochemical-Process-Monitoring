# Petrochemical Process Monitoring System

A Python-based engineering tool designed to monitor, filter, and analyze operational data from a distillation unit using **SQLite**, **SQL queries**, and **Pandas**.

## Overview
Industrial chemical plants require automated anomaly detection to prevent equipment damage and operational downtime. This project simulates operational logs (temperature, pressure, feed rate) from a distillation column, stores them in an SQLite database, and automatically flags potential operational risks such as over-temperature or heat exchanger fouling.

## Features
- **Database Architecture:** Uses `sqlite3` with Python Object-Oriented Programming (OOP) to create and query relational tables.
- **Data Filtering:** Executes SQL queries to extract parameters exceeding critical operating thresholds.
- **Engineering Analytics:** Uses Pandas to compute diagnostic alerts:
  - **High Temperature Alert:** Flagged when outlet temperature exceeds $350^\circ\text{C}$.
  - **Fouling Risk Alert:** Flagged when heat exchanger/column pressure drop ($\Delta P$) exceeds $15\text{ psi}$.

## Stack & Tools
- **Language:** Python 3
- **Data Libraries:** Pandas, SQLite3
- **Engineering Context:** Distillation column operations & anomaly detection

## How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/petrochemical-process-monitoring.git](https://github.com/YOUR_USERNAME/petrochemical-process-monitoring.git)
