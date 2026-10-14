# SARS 2003 Outbreak Analysis

Exploratory analysis of the 2003 SARS outbreak in R: cases, deaths and recoveries over time, recovery rates by country, and a world map of confirmed cases.

**Authors:** Nabeela Khan & Sowmya Tummala

## Project structure

```
.
├── sars_2003_analysis.Rmd                  # the analysis (R Markdown)
├── data/
│   └── sars_2003_complete_dataset_clean.csv
├── README.md
└── .gitignore
```

## How to run

1. Install R and RStudio.
2. Install the required packages (once):
   ```r
   install.packages(c("tidyverse", "plotly", "kableExtra", "knitr", "maps"))
   ```
3. Open `sars_2003_analysis.Rmd` in RStudio and click **Knit**.
   (The file path is relative, so open the project from its own folder.)

## What it covers

- Data cleaning checks (dimensions, column types, duplicates, dates)
- Cumulative confirmed cases, deaths and recoveries over time
- Top ten countries by recovery rate and by death count
- Distribution of recovery rates across countries
- Interactive world map of maximum confirmed cases

## Data

SARS 2003 complete dataset (daily cumulative confirmed cases, deaths and recoveries by country).
