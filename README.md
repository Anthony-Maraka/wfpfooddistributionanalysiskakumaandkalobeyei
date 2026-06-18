# WFP Food Distribution Analysis — Kakuma & Kalobeyei

This repository contains a digital skills analysis for WFP food distribution in the Kakuma and Kalobeyei refugee settlements.

## Overview

This project analyzes food distribution data from WFP for the Kakuma and Kalobeyei camps. The analysis includes data cleaning, exploratory analysis, visualizations, and an interactive dashboard to help stakeholders understand distribution patterns, beneficiary reach, and operational metrics.

## Files in this repository

- WFP_Food_Distribution_Kakuma_Kalobeyei.xlsx — Raw dataset (Excel)
- WFP_Food_Distribution_Analysis_Report.pdf — Full analysis report (PDF)
- README.md — This file

## Dashboard screenshots

Below are placeholders for dashboard screenshots. To include your actual dashboard images, add them to the repository at `docs/screenshots/` (create the folder if it does not exist) and name them as shown. The images will render automatically in this README once they are pushed.

- docs/screenshots/dashboard_overview.png — Dashboard overview (key KPIs and maps)
- docs/screenshots/dashboard_filters.png — Filters and interactive controls
- docs/screenshots/dashboard_trends.png — Time series and trends

Example display (placeholders):

![Dashboard overview](docs/screenshots/dashboard_overview.png)

![Dashboard filters](docs/screenshots/dashboard_filters.png)

![Dashboard trends](docs/screenshots/dashboard_trends.png)

If you prefer different file names, update the image paths above accordingly.

## How to reproduce the analysis

1. Open `WFP_Food_Distribution_Kakuma_Kalobeyei.xlsx` in Excel (or import into Python/R) — this file contains the raw data used for analysis.
2. Review the methodology and findings in `WFP_Food_Distribution_Analysis_Report.pdf`.
3. If you have a dashboard project file (Power BI `.pbix`, Tableau `.twbx`, Dash/Streamlit app folder, or a static `dashboard.html`), place it in the repository (for large Power BI files consider adding to Releases or keeping locally and linking in this README).

Suggested reproducible environment (example):

- Python 3.8+ with pandas, numpy, matplotlib/seaborn, geopandas (if mapping), and plotly or dash for interactive dashboards.
- R 4.0+ with tidyverse, sf (for spatial) and shiny (for interactive dashboards).

## Adding your dashboard screenshots (quick guide)

1. Create the folder `docs/screenshots/` in the repository root.
2. Save your screenshots as PNG (e.g., `dashboard_overview.png`, `dashboard_filters.png`, `dashboard_trends.png`).
3. Commit the images and push to the repository. The images will render in this README automatically.

Example Git commands:

```
mkdir -p docs/screenshots
cp /path/to/your/screenshot1.png docs/screenshots/dashboard_overview.png
cp /path/to/your/screenshot2.png docs/screenshots/dashboard_filters.png
cp /path/to/your/screenshot3.png docs/screenshots/dashboard_trends.png
git add docs/screenshots/*.png
git commit -m "Add dashboard screenshots"
git push
```

If you want, I can add the screenshots for you — upload them here or provide public URLs and I will add them to the repository and update the README to point to them.

## How to cite / contact

Author: Anthony Maraka
Repo: Anthony-Maraka/WFP-Food-Distribution_Analysis-Kakuma-and-Kalobeyei

For questions or collaboration, open an issue or contact me at the address listed on my GitHub profile.

---

Licensed under CC BY-NC-SA (add your preferred license file `LICENSE` if desired).
