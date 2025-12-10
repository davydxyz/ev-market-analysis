# EV Power: Clean Energy and Electric Vehicles Analysis

A data analysis project exploring the relationship between electric vehicle adoption and renewable energy sources across U.S. states.

## Research Question

**Electric vehicles reduce direct emissions, but does the electricity used to charge them actually come from clean sources?**

## Project Overview

This project analyzes energy data from 2021-2023 to understand:
- Renewable energy usage patterns across U.S. states
- Trends in clean energy adoption over time
- The relationship between EV registrations and renewable energy availability
- Geographic patterns in energy pricing and renewable energy sources

## Datasets

The project uses the following datasets (2021-2023):

- **Renewable Energy Use by State**: Annual renewable energy consumption by state
- **Total Energy Use by State**: Total energy consumption across all sources
- **Average Energy Prices**: State-level electricity pricing data
- **EV Registrations by State**: Electric vehicle registration counts (2023)

All data files are located in the [data/](data/) directory.

## Key Findings

Analysis of the top 10 renewable energy states reveals:

1. **Consistent Growth**: Renewable energy rates increased steadily from 2021 to 2023 across all top-performing states
2. **State Variations**: Some states (e.g., California, New Mexico) showed rapid growth, while others (Indiana, Utah) maintained consistently high renewable rates
3. **National Trend**: The overall U.S. energy grid is becoming cleaner, meaning EVs are increasingly powered by renewable sources

## Project Structure

- [report.qmd](report.qmd) - Main analysis report with data cleaning, joining, and visualization code
- [project.qmd](project.qmd) - Project instructions and requirements
- [worksheet.qmd](worksheet.qmd) - Lab worksheet exercises
- [ev-dashboard.qmd](ev-dashboard.qmd) - Optional interactive dashboard (Quarto Dashboard)
- [data/](data/) - All CSV datasets

## Technologies Used

- **R** with tidyverse for data manipulation
- **Quarto** for reproducible reporting
- **ggplot2** for data visualization
- String manipulation and data cleaning techniques

## Getting Started

1. Clone this repository
2. Open the project in RStudio or Positron
3. Install required packages: `tidyverse`, `stringr`
4. Run [report.qmd](report.qmd) to reproduce the analysis

## Author

Project completed for Stat 133 - Fall 2024
