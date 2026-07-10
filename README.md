# India Tourism Trend Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Matplotlib-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

Exploratory data analysis of Indian tourism trends across 40 years (1981–2021) — covering international arrivals, quarterly patterns, purpose of visit, age demographics, state-wise distribution, monument footfall, and India's global tourism ranking.

---

## Analysis Sections

| # | Section | Dataset | Period |
|---|---|---|---|
| 1 | International Tourist Arrivals (FTA / NRI / ITA) | `fta_nri_ita.csv` | 1981–2020 |
| 2 | Quarterly Distribution of Tourist Arrivals | `quaterly.csv` | 2001–2019 |
| 3 | Purpose of Visit (Business / Leisure / Medical) | `region-and-reason.csv` | 2019 |
| 4 | Market Share by Region & Country | `region-2017-2019.csv` | 2017–2019 |
| 5 | Age Group Distribution of FTAs | `agegroup.csv` | 2001–2019 |
| 6 | State-wise Domestic & Foreign Tourists | `statewise_2019-2020.csv` | 2019–2020 |
| 7 | Monument Footfall (Top 10 domestic & foreign) | `monuments.csv` | 2019–2021 |
| 8 | India's Global Tourism Ranking | `worldvsindia.csv` | 2001–2021 |

---

## Key Findings

**International Arrivals (1981–2020)**
- FTAs grew from **1.28M (1981)** to a peak before COVID-19 induced a sharp decline in 2020
- NRI and ITA arrivals tracked FTA growth across decades

**Quarterly Distribution (2001–2019)**
- Tourism is seasonally skewed: Q1 (Jan–Mar) and Q4 (Oct–Dec) dominate
- Average quarterly split: **28.8% Q1 · 19.2% Q2 · 21.6% Q3 · 30.3% Q4**
- Peak season is Oct–Mar; Apr–Sep sees consistent off-peak dip

**Purpose of Visit (2019)**
- Grand Total breakdown: Leisure/Recreation dominates, followed by Indian Diaspora, Business, Medical
- Top arrivals by region: North America leads, followed by Western Europe

**Age Group (2001–2019)**
- Dominant age bands: **35–44 (20.9%)** and **25–34 (18.4%)**
- Consistent across two decades — prime working age drives international travel to India

**State-wise (2019–2020)**
- **Foreign tourists:** Tamil Nadu (#1, 68.7 lakh), Maharashtra (#2, 55.3 lakh), UP (#3, 47.5 lakh)
- **Domestic tourists:** Uttar Pradesh (#1, 5,358 lakh), Tamil Nadu (#2, 4,948 lakh)
- COVID-19 impact clearly visible: 2020 figures ~75–80% lower across all states

**Monuments (2019)**
- **Top foreign destination:** Taj Mahal, Agra — 645K foreign visitors
- **Top domestic destination:** Taj Mahal again — 4.4M domestic visitors
- Agra circle leads all ASI circles for foreign tourists

**Global Ranking**
- India's share of global tourism rose steadily from 2001 → ~0.68% of world arrivals by 2019

---

## Repository Structure

```
Tourism-Trend-Analysis/
├── India Tourism Analysis.ipynb    # 110-cell EDA notebook
├── Big Data Proj PPt.pptx          # Project presentation
├── Big Data Project Links.txt      # Repo + recording links
├── Data set/                       # 8 CSV datasets
│   ├── India-Tourism-Statistics-1981-2020-fta_nri_ita.csv
│   ├── India-Tourism-Statistics-2001-2019-quaterly.csv
│   ├── India-Tourism-Statistics-2001-2019-agegroup.csv
│   ├── India-Tourism-Statistics-2001-2019-worldvsindia.csv
│   ├── India-Tourism-Statistics-2019_region-and-reason.csv
│   ├── India-Tourism-Statistics-region-2017-2019.csv
│   ├── India-Tourism-Statistics-statewise_2019-2020_domestic_foreign.csv
│   └── India-Tourism-Statistics-2021-monuments.csv
├── output images.zip               # All generated chart outputs
└── pbi and pipeline imgs.zip       # Power BI dashboard screenshots
```

---

## Setup & Run

```bash
git clone https://github.com/saiswaroopkakarla/Tourism-Trend-Analysis.git
cd Tourism-Trend-Analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook "India Tourism Analysis.ipynb"
```

Run all cells (`Kernel → Restart & Run All`). All datasets are in `Data set/` — no external downloads needed.

---

## Visualisation Types Used

| Chart type | Used for |
|---|---|
| Multi-line plot | FTA/NRI/ITA trends, age group trends over time |
| Bar plot (vertical) | Total arrivals by year, monument footfall |
| Bar plot (horizontal) | State-wise foreign & domestic tourists |
| Pie chart | Quarterly distribution, purpose of visit, age group averages |
| Area plot | Region-wise purpose of visit |
| Subplot grids | Quarterly distributions (2017/2018/2019 side-by-side) |

---

## Data Source

All datasets sourced from the **Ministry of Tourism, Government of India** — India Tourism Statistics reports (2020, 2021 editions). Available at [tourism.gov.in](https://tourism.gov.in).

---

## Author

**Kakarla Sai Swaroop** — M25DE1023, IIT Jodhpur M.Tech Data Engineering  
Course: CSL7110  ML with Big Data
