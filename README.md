# Himalayan Climbing Expeditions  
**Authors:** Siva Adharsh, Calvin Soe Frederick, Goh Si Xian, Amanda, Yashita Makhijani, Nathanial Teo  

---

## Project Overview  
This analysis investigates the factors that influence the success rate of Himalayan climbing expeditions. Using the 2025 TidyTuesday “History of Himalayan Mountaineering” dataset and complementary elevation data, we:

1. Cleaned and merged multiple data sources.  
2. Computed key summary statistics.  
3. Created visualisations to uncover trends over time and by region.  
4. Discussed insights and limitations.

---

## Table of Contents  
- [Introduction](#introduction)  
- [Data Preparation](#data-preparation)  
- [Summary Statistics](#summary-statistics)  
- [Data Visualization](#data-visualization)  
- [Discussion](#discussion)  
- [Team Roles](#team-roles)  
- [References](#references)  

---

## Introduction  
We posed the guiding question:  
> **What influences the success rate of Himalayan climbing expeditions?**  

To answer this, we explored variables such as country of origin, elevation profiles, and temporal trends in expedition outcomes.

---

## Data Preparation  
- **TidyTuesday dataset**: Imported “History of Himalayan Mountaineering Expeditions” by Nicolas Foss (2025-01-21) 
- **Elevation data**: Retrieved country elevation statistics from WorldPopulationReview (2025)
- **Wrangling steps**:  
  - Standardised column names with **dplyr**.  
  - Filtered out incomplete entries.  
  - Joined the expedition and elevation tables on country codes.

---

## Summary Statistics  
- Calculated overall and per-country success rates.  
- Identified top-performing expeditions by decade.  
- Tabulated mean maximum elevations reached per country.

---

## Data Visualisation  
- **Time series** of expedition counts vs. success rate.  
- **Bar charts** ranking countries by average success.  
- **Scatter plots** correlating elevation with success.  
Each plot was created using **ggplot2** layered with **dplyr** summaries for clarity.

---

## Discussion  
- **Key findings**:  
  - Success rates have generally climbed over time, coinciding with improved equipment and training.  
  - Higher-elevation countries exhibit a slight dip in success, suggesting altitude challenges despite experience.  
- **Limitations**:  
  - Potential reporting bias in early expedition records.  
  - Lack of team composition and weather variables.

---

## References  
1. Foss, N. (2025). *The History of Himalayan Mountaineering Expeditions* [Data set]. TidyTuesday (2025-01-21). :contentReference[oaicite:3]{index=3}  
2. “Elevation by country 2025.” *WorldPopulationReview*. :contentReference[oaicite:4]{index=4}  
3. Bhandari, S., et al. (2015). *Genetic evidence of a recent Tibetan ancestry to Sherpas in the Himalayan region*. *Scientific Reports*, 5, 16249. :contentReference[oaicite:5]{index=5}  
4. Annapurna avalanche kills two Nepali climbers. (2025, April 8). *Phys.org*. :contentReference[oaicite:6]{index=6}  


