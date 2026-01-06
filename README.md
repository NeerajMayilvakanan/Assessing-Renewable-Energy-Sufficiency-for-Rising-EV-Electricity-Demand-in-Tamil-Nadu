# Assessing Renewable Energy Sufficiency for Rising EV Electricity Demand in Tamil Nadu

## Project Overview
Tamil Nadu is emerging as one of India’s leading electric vehicle (EV) hubs. As EV adoption accelerates, electricity demand increasingly shifts to the power grid. This project evaluates whether Tamil Nadu’s renewable energy generation can sustainably support the rising electricity demand from EV charging between 2026 and 2036.

The study combines historical energy data, EV adoption trends, and forecasting models to assess long-term renewable adequacy under multiple EV growth scenarios.

---

## Problem Statement
With rapid EV adoption driven by policy support and technological improvements, a key concern is whether renewable electricity generation—characterized by variability and capacity constraints—can meet future EV charging demand without increasing dependence on fossil fuels.

This project answers:
- How fast will EV electricity demand grow?
- How much renewable electricity is likely to be available?
- Will EV charging strain Tamil Nadu’s renewable energy system?

---

## Data Sources
The analysis is based entirely on secondary government and public datasets:
- Renewable and non-renewable electricity generation data (NDAP)
- EV registration data (Parivahan Dashboard – web scraped)
- Population data (Census and projections)
- Per-capita electricity consumption data (CEA)

Historical data covers 2006–2025, with forecasts extended to 2036.

---

## Methodology
- **Exploratory Analysis (2006–2025)**  
  Studied historical trends in electricity generation, demand, and EV adoption.

- **EV Electricity Demand Forecasting**  
  Used a Logistic S-Curve model to estimate EV electricity load under:
  - Low adoption scenario  
  - Mid (realistic) adoption scenario  
  - High adoption scenario  

- **Renewable Energy Forecasting**  
  Applied a 3-year trailing moving average to smooth renewable generation variability and create baseline projections.

- **Adequacy Assessment**  
  Computed the Renewable Adequacy Ratio (RAR):

RAR = Renewable Generation / EV Electricity Load

This metric evaluates whether renewable electricity is sufficient to meet EV charging demand.

---

## Key Insights
- EV electricity demand remained negligible until 2020 but accelerated sharply after 2022.
- By 2036, EV electricity demand is projected to range from ~1,000 GWh (Low) to ~3,000 GWh (High).
- Renewable generation remains sufficient under all scenarios throughout the forecast period.
- Even in the high adoption case, EV charging consumes less than 9% of total renewable electricity by 2036.
- Declining adequacy ratios indicate the importance of continued renewable capacity expansion.

---

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib  
- SciPy (curve fitting)  
- Selenium (data scraping)  
- Jupyter Notebook  

---

## Repository Structure
├── Project.ipynb
├── energy_dataset.csv
├── energy_development.csv
├── tamilnadu_vehicles_reg.csv
├── population.csv
├── per_capita_consumption.csv
├── forecasted_renew_gen.png
└── README.md


---

## Conclusion
The analysis indicates that Tamil Nadu’s renewable energy system can support rising EV electricity demand until at least 2036. However, declining adequacy trends highlight the need for sustained renewable capacity additions and long-term energy planning to support large-scale EV adoption.

---
