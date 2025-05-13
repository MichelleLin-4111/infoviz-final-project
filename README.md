# Mapping the Risk: Health Workers in Conflict and Political Violence Zones 

**Info 247: Information Visualization Final Project**

By Ann Yu, Jessie Deng, and Michelle Lin

This project explores patterns of violence against healthcare workers in conflict-affected regions, with a focus on Afghanistan, India, Iran, and Pakistan from 2017 to 2024. Using data from ACLED (Armed Conflict Location & Event Data), we analyze regional hotspots, trends over time, and types of conflict events involving health workers. The goal is to raise awareness and support organizations like Doctors Without Borders (DWB) in planning safer healthcare delivery in volatile areas.

[View the Live Project Site](https://sites.google.com/berkeley.edu/infovizproject/home)

## Repository Contents
- **dwb.ipynb**: 
Main Jupyter notebook for fetching, cleaning, and preprocessing the datasets. Includes filtering by country, and year.

- **healthworkers.csv**:
Raw dataset exported from ACLED, containing incident-level records of disorders involving healthcare workers globally.

- **health_workers_combined_2017_2024.csv**:
Cleaned and filtered dataset used for visualizations and analysis, limited to 2017–2024 and the four focus countries.

- **acled_data_004.json**:
This file contains geospatial conflict event data from ACLED, detailing political violence, demonstrations, and strategic developments by or affecting political actors around the world.

## Observable Notebooks
You can view and explore our visualizations via Observable:
- [Heatmap, Line Chart, Grouped Bar Charts](https://observablehq.com/d/76ca5b0ed48e03f9)
- [Types of Disorders Tree Graph](https://observablehq.com/d/9fb6840890564f26)

## Data Source
All conflict and incident data used in this project are sourced from:
[ACLED (Armed Conflict Location & Event Data)](https://acleddata.com/)
