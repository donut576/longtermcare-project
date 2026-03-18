# Taoyuan City LTC 2.0 — Workforce Supply–Demand Gap Analysis

## Project Overview
This project investigates the critical workforce bottleneck in Taoyuan City’s Long-Term Care (LTC) 2.0 system. By integrating Prophet time-series forecasting and a Gemini-powered RAG system, we identify a widening gap between elderly care demand and professional supply.

## Environment Setup
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the notebook:
   ```
   jupyter notebook Final_112403012.ipynb
   ```

## Dataset
Raw data files are placed in the `data/` folder, sourced from the [Taoyuan City Government Open Data Platform](https://data.gov.tw/dataset/149270).

| File | Description |
|---|---|
| `Taoyuan Home Care Training Participants.csv` | Annual home-care training headcount (2011–2018) |
| `Taoyuan Day Care Dementia Cases.csv` | Day-care dementia case counts (2004–2017) |
| `Taoyuan LTC Institutions Occupancy.csv` | Institutional resident counts (2004–2024) |
| `LTC 2.0 Care Workers (Taiwan).csv` | National care-worker snapshot (2024) |
| `Taoyuan LTC Institution Staff by Type.csv` | Staff breakdown by role (2013–2024) |

## Notebook Structure
| Chapter | Content |
|---|---|
| 0 | Environment setup |
| 1 | Project background & research questions |
| 2 | Data loading & cleaning |
| 3 | Descriptive statistics & gap analysis |
| 4 | Visualisation (trend chart, correlation heatmap) |
| 5 | Statistical modelling & Prophet forecast (2025–2027) |
| 8 | Conclusions & policy recommendations |

