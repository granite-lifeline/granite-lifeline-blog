---
title: About
icon: fas fa-info-circle
order: 4
---

## About This Project

Granite Lifeline is an IBM-sponsored MSc Computer Science group project at the University of Bristol, developed between June and September 2026.

The project builds an end-to-end predictive maintenance system for engine components, using OBD-II (On-Board Diagnostics) time-series data to detect anomalies and generate human-readable diagnostic reports.

## System Architecture

The system is built on three layers:

- **Data Layer** — Ingests and preprocesses the KIT Automotive OBD-II dataset, performs feature engineering and anomaly scenario simulation
- **Model Layer** — Uses IBM Granite TTM for time-series anomaly detection and failure risk scoring
- **Report Layer** — Uses IBM Granite LLM to generate structured natural language diagnostic reports, including anomaly description, probable root cause, and recommended inspection actions

## The Team

| Member | Role |
|---|---|
| Charlotte | System Integration & Report Layer |
| Tong | Report Layer|
| Layla | Data Layer |
| Fu | Data Layer |
| Lucca | Model Layer |
| Ray | Model Layer |

## Links

- [GitHub Repository](https://github.com/granite-lifeline)
- [University of Bristol](https://www.bristol.ac.uk)
