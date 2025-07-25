# COVID‑19 in India Analysis Dashboard 📊

An interactive and comprehensive Tableau dashboard offering deep insights into the COVID‑19 pandemic in India.

---

## 🚀 Overview

This Tableau workbook presents a multi‑facet analysis of the COVID‑19 situation in India—tracking trends, demographics, testing, vaccination, and state‑wise distribution. Built to be user‑friendly, it’s ideal for researchers, policymakers, and public health professionals.

---

## 📂 Dashboard Features

- **State‑wise Map Visualizing Total Deaths**: Choropleth view highlighting mortality hotspots across Indian states :contentReference[oaicite:1]{index=1}  
- **Time Series Trendlines**: Dynamic line charts showing cumulative confirmed, recovered, and death cases over time :contentReference[oaicite:2]{index=2}  
- **Age Group Distribution**: Breakdown of cases by age categories, pointing out vulnerable segments :contentReference[oaicite:3]{index=3}  
- **Gender-Based Analysis**: Visualization of male vs female case distribution, excluding or addressing missing values :contentReference[oaicite:4]{index=4}  
- **State-Level Testing Data**: Insight into state-wise ICMR testing labs, total tests, and positivity rates :contentReference[oaicite:5]{index=5}  
- **Vaccination Rollout Metrics**:
  - First vs. second dose comparison
  - Vaccine type distribution (Covishield, Covaxin, Sputnik V) :contentReference[oaicite:6]{index=6}  

---

## 🛠 Workbook Details

- **Data Sources**: Aggregated from official government portals, ICMR/Ministry of Health, and credible open datasets (e.g. Kaggle and state releases) :contentReference[oaicite:7]{index=7}  
- **Data Preparation**: Utilized CSV files including state-wise counts, demographic breakdowns, testing and vaccine info; blended via Tableau, also using shapefiles for India maps :contentReference[oaicite:8]{index=8}  
- **Visual Design**:
  - Combined charts: line, bar, stacked bar, doughnut/pie visuals
  - Dual‑axis for overlay trends
  - Interactive filters for time period, state, gender, age group

---

## 🔧 What You (or a Contributor) Have Done

1. Imported multiple datasets: cases, testing, vaccination, demographic.
2. Blended data via shared keys (state, date).
3. Created map visualizations with custom shape files.
4. Built interactive sheets: time‑series charts, demographic metrics, vaccine comparisons.
5. Assembled a dashboard with synchronized filters and tooltips.
6. Configured interactivity: selections by state, date slider, demographic toggles.
7. Ensured clean data: handled missing values in gender and age breakdowns.

---

## 📝 Use Cases

- **Track pandemic progression**, key waves, and regional hotspots.  
- **Compare demographic impacts** by age/gender.  
- **Assess vaccine adoption** across doses and types.  
- **Monitor testing infrastructure** and positivity variation across states.  
- **Inform public health strategy** and policy intervention decisions.

---

## ▶️ Viewing & Access

- Open the Tableau workbook (`.twb` or `.twbx`) in **Tableau Public** or **Tableau Desktop**.  
- Navigate the interactive dashboard to explore filters and chart interactivity.

---

---

## ⚙️ Technologies Used

- **Tableau Desktop/Public** – for data blending, visualization & dashboard creation  
- **CSV / Shapefile** formats – for input data  
- **Interactive filters and tooltips** – for user‑driven exploration  

---

## 🙏 Acknowledgments

- Source data from government health portals, ICMR and official APIs  
- Tableau Public platform and embedded map features  
- Inspiration from other Tableau COVID‑19 dashboards showcasing demographic, testing, and vaccination trends :contentReference[oaicite:9]{index=9}

---

## 📌 Notes

- Dataset may be based up to **[your last update date]**.  
- Some missing values exist in demographic fields; appropriate filters applied to ensure clarity in visualizations.  

---

Feel free to edit or expand this README as needed to match your exact workbook content and structure. Happy to help further if you'd like to include technical details like filters, calculated fields, or compute logic you applied!
::contentReference[oaicite:10]{index=10}


