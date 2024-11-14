# Motus NE Analysis

Interactive visualization of migratory bird movements in the Northeastern United States using 
[Motus Wildlife Tracking System](https://motus.org/) telemetry data. This analysis combines 
[Folium](https://python-visualization.github.io/folium/) for interactive mapping and 
[MovingPandas](https://movingpandas.org/) for trajectory analysis.

## Overview

This project visualizes bird migration patterns using data from the Motus Wildlife Tracking System. The interactive maps show:
- Bird detection locations
- Movement trajectories
- Temporal patterns of migration
- Receiver station locations

## Project History

This analysis is an updated version of a Masters of Environmental Studies capstone project originally submitted by Keon Monroe in  2019. 

The current version features enhanced visualizations and updated data processing techniques.

## View the Analysis

View the interactive maps and full analysis on nbviewer:
[View Notebook](https://nbviewer.org/github/[your-username]/motus-ne-analysis/blob/main/notebooks/motus-wrangling-analysis-2024.ipynb)

## Data Source

Data is sourced from the [Motus Wildlife Tracking System](https://motus.org/), 
a collaborative research network that tracks the movement and behavior of small flying organisms (mainly birds).
The specific data used in this analysis is from the [Northeast Motus Collaboration](https://www.northeastmotus.com/).

## Tools Used
- Python 3.11 
    - Jupyter and nbviewer for interactive analysis
    - Folium: Interactive mapping
    - MovingPandas: Trajectory analysis
    - GeoPandas: Spatial data handling
