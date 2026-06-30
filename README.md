# Global-Well-Being-Analytics
Power BI dashboard analysing the relationship between GDP, unemployment rate, and happiness scores across 100+ countries using World Happiness Report data (1991–2023).
# 🌍 Global Well-Being Analytics — World Happiness & Unemployment Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![World Happiness Report](https://img.shields.io/badge/WHR%20Dataset-34A853?style=for-the-badge&logo=google&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

## 📌 Project Overview

This Power BI project analyses the relationship between **economic prosperity, unemployment, and human happiness** across countries and decades. By combining the **World Happiness Report (WHR)** dataset with global **unemployment rate** data, the dashboard surfaces how societal and economic factors — GDP per capita, job stability, freedom, and healthy life expectancy — collectively drive well-being outcomes worldwide.

The project was built to answer a core question: **do wealthier, more employed nations produce happier citizens — and by how much?**

---

## 📊 Dashboard Pages

### Page 1 — Unemployment Dashboard
Explores the relationship between unemployment rates and life satisfaction at both country and global level.

| Visual | Description |
|--------|-------------|
| Scatter Plot | Average Unemployment Rate vs Average Life Ladder by Country |
| World Map (Bubble) | Average Unemployment Rate by Country — geographic distribution |
| Line Chart | Unemployment Rate & Freedom to make life choices over time (1990–2023) |
| KPI Cards | Average Life Ladder · Average Unemployment Rate · Average Healthy Life Expectancy |
| Slicers | Country name · Year |

### Page 2 — GDP Per Capita Dashboard
Analyses how economic output correlates with happiness, freedom, and healthy life expectancy.

| Visual | Description |
|--------|-------------|
| Scatter Plot | Min GDP per capita vs Average Life Ladder by Country |
| World Map (Bubble) | Average GDP per capita by Country |
| Dual-axis Line Chart | Life Ladder & Freedom to make life choices over time |
| Grouped Bar Chart | Life Ladder & Healthy life expectancy at birth by Country |
| Line Chart | Average Life Ladder trend by Year |
| KPI Cards | Avg GDP per capita · Avg Life Ladder · Avg Healthy life expectancy |
| Slicers | Country name · Year |

---

## 🔑 Key Findings

| Metric | Global Average |
|--------|---------------|
| 😊 Life Ladder (Happiness Score) | **5.49 / 10** |
| 💰 GDP per capita (log scale) | **9.40** |
| 💼 Unemployment Rate | **8.55%** |
| 🕊️ Freedom to make life choices | **0.75 / 1.0** |
| 🏥 Healthy life expectancy at birth | **63.40 years** |

### Correlation Insights
- **Positive correlation confirmed:** Higher GDP per capita consistently maps to higher Life Ladder scores — wealth measurably boosts happiness
- **Negative correlation confirmed:** Higher unemployment correlates with lower freedom scores — job stability directly enhances personal autonomy
- **Regional disparity:** Significant variance in both happiness and unemployment across regions — Northern European nations consistently outperform on Life Ladder scores
- **Time trend:** Freedom to make life choices showed gradual improvement from the 1990s through 2020, with a notable dip around 2020–2023

---

## 💡 Business & Policy Implications

**For High Unemployment Regions:**
Organisations and governments can use this data to prioritise employment programmes and job security initiatives — directly linked to improvement in freedom and happiness scores.

**For Low Happiness Scores:**
Investment in personal freedom infrastructure (healthcare access, social support) shows measurable impact on Life Ladder outcomes even in lower-GDP economies.

**For Regional Disparities:**
Resources directed at regions with high unemployment and low Life Ladder scores produce the greatest marginal improvement in global well-being metrics.

**Benchmarking:**
Countries with high Life Ladder scores despite economic challenges (e.g., Costa Rica, New Zealand) provide a replicable model — showing that happiness is not exclusively GDP-dependent.

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard design, data modelling, DAX measures |
| **Microsoft Excel** | Data preparation and cleaning |
| **World Happiness Report (WHR)** | Primary happiness dataset — Life Ladder, GDP, Freedom, Health |
| **Global Unemployment Dataset** | Unemployment rate by country and year |

---

## 📁 Repository Structure

```
world-happiness-unemployment-analysis/
│
├── README.md
├── World_Happiness_Dashboard.pbix          # Power BI source file
├── World_Happiness_Dashboard.pdf           # Exported dashboard (PDF)
│
├── data/
│   ├── world_happiness_report.csv          # WHR dataset
│   └── unemployment_rate_global.csv        # Unemployment dataset
│
├── screenshots/
│   ├── 01_unemployment_dashboard.png
│   ├── 02_gdp_per_capita_dashboard.png
│   ├── 03_scatter_gdp_vs_life_ladder.png
│   └── 04_world_map_unemployment.png
│
└── presentation/
    └── Global_Wellbeing_Insights.pptx      # Original presentation deck
```

---

## 🚀 How to Use

1. **Clone or download** this repository
2. Open `World_Happiness_Dashboard.pbix` in **Power BI Desktop** (free download from Microsoft)
3. If prompted, refresh the data source and point it to the `/data/` folder
4. Use the **Country name** and **Year** slicers to filter to specific regions or time periods
5. View the exported `World_Happiness_Dashboard.pdf` for a static version requiring no software

---

## 📌 Data Sources

- **World Happiness Report** — Gallup World Poll data, published annually. Metrics include: Life Ladder, Log GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, Perceptions of corruption
- **Global Unemployment Rate** — Multi-decade country-level unemployment data spanning 1991–2023

---

## 👤 About

**Kartik Kodilkar** — ITSM Professional & Data Analyst (MSc Business Analytics, Dublin Business School, 2025 — First Class Honours)

- 🔗 [LinkedIn](https://linkedin.com/in/kartik-kodilkar)
- 💻 [GitHub Portfolio](https://github.com/kartikkodilkar-netizen)
- 📍 Dublin, Ireland

*This project is part of a data analytics portfolio demonstrating proficiency in Power BI, data modelling, and business insight generation.*

---

> *"Data is the new oil — but insight is the refinery."*
