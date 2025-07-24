# Excess Deaths During the COVID-19 Pandemic in Scotland

This project investigates the **weekly excess mortality** in Scotland during the COVID-19 pandemic (2020–2022) using **time series analysis**. It was completed as part of my MSc in Data Science.

## Abstract

Mortality statistics are critical for public health decisions. This project estimates excess deaths in Scotland across multiple locations, genders, and causes during the pandemic. By comparing weekly deaths in 2020–2022 to a pre-pandemic baseline (2015–2019), the study identifies COVID-19-related trends and other factors contributing to increased mortality.

## Research Questions

- What is the total excess death count in Scotland during 2020–2022?
- How did COVID-19 and non-COVID-19 deaths evolve over time?
- What patterns exist by **gender**, **cause of death**, and **location** (home, care home, hospital)?
- Were there time-based spikes or anomalies in excess deaths?

## Methods

- **Time Series Analysis** on weekly mortality data
- Baseline expected deaths computed from 2015–2019
- Actual deaths compared to expected deaths to calculate excess deaths
- Separate analysis by:
  - Cause of death (COVID-19 underlying, contributory, non-COVID)
  - Gender
  - Location (hospital, care home, home, other institutions)

## Data Sources

Data obtained from the **National Records of Scotland (NRS)**:
- Weekly deaths by council area, sex, and age (2015–2019)
- Weekly deaths by health board, cause, and gender (2020–2022)
- Weekly deaths by location of death (2015–2022)

All datasets are in CSV format and were cleaned, transformed, and analyzed using Python.

## Tools Used

- **Language:** Python 3.10  
- **Environment:** Jupyter Notebook  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Techniques:** Data cleaning, aggregation, time series analysis, visualizations

## Key Results

- **2020** had the highest number of excess deaths, with a total of **7,194.6**
- **2022** showed the lowest excess deaths across the three years
- Clear spikes were observed during lockdowns and COVID-19 waves
- Non-COVID deaths also increased, likely due to delayed care and systemic strain

Visualizations are included in the notebooks, with breakdowns by:
- Gender
- Location of death
- Cause of death (COVID-19 vs non-COVID)

## Repository Contents

| File | Description |
|------|-------------|
| `01_preprocessing_and_baseline.ipynb` | Data cleaning and expected deaths baseline (2015–2019) |
| `02_excess_deaths_analysis.ipynb`     | Time series comparison and excess deaths results (2020–2022) |
| `/data`                               | Raw CSV files used for analysis |
| `figures/`                            | Saved plots and visualizations |
| `dissertation_summary.pdf` *(optional)* | Final report or slide deck |

## Author

**Khushboo Masih**  
MSc in Data Science  
Email: khushboomasih193@gmail.com  
LinkedIn: https://www.linkedin.com/in/khushboo-masih/

## License

This project is for educational and academic purposes. Data belongs to the National Records of Scotland. No commercial use permitted.
