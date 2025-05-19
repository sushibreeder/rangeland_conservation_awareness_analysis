# Rangeland Conservation Awareness Analysis

This project analyzes survey data collected from three age groups (14–18, 19–40, 41+) to assess learning gains and perceptions about grassland conservation practices.

## Objectives

- Evaluate how prior experience (fire, grazing, management) affects conservation learning gains
- Test associations using Chi-Square and Fisher’s Exact Tests
- Measure relationship strength with Cramér’s V
- Identify motivation factors impacting learning

## Dataset

Survey responses were provided as separate files by age group and merged for analysis. Final dataset includes 157 responses and 44 variables.

Data files (not hosted due to size) include:
- Questions
- Results for age groups: 14–18, 19–40, and 41+

## Repository Structure

- `scripts/`: Python code for data cleaning, merging, analysis, and plotting
- `data/`: File structure description or small samples
- `reports/`: Final project report (PDF or DOCX)
- `figures/`: Visualizations (heatmaps, bar charts, etc.)

## Methods

- Chi-Square Test for Independence
- Fisher’s Exact Test
- Cramér’s V for effect size
- Visualizations using seaborn/matplotlib

## Requirements

Python packages:
- pandas
- seaborn
- matplotlib
- scipy
- numpy

## License

MIT License
