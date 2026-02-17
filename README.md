# Data Science Analysis of Football GPS Tracking

## Authors : Théo Lecomte

This repository contains data, tools, and scripts for analyzing professional football GPS tracking data. It provides the framework to clean raw tracking data, compute performance metrics, visualize player and team behavior, and explore tactical analysis. The project is licensed under the GNU General Public License v3 (GPLv3).

---

## Summary
1. [Overview](#overview)  
2. [Project Structure](#project-structure)
3. [Requirements](#requirements)  
4. [Getting Started](#getting-started)  
5. [Launch](#launch)
6. [Licence](#licence)  

---

## Overview 

This project allows you to:

-Clean and preprocess GPS tracking data for 42 players across training sessions and matches.

-Detect and handle position and speed outliers using custom algorithms.

-Compute individual athletic metrics: speed zones, acceleration/deceleration counts, maximum speed, distance covered, and training load.

-Generate radar charts to visualize player profiles and signatures.

-Analyze team performance using dynamic visualizations and heatmaps.

-Explore tactical patterns, defensive line structure, and key event analysis.

-Develop predictive insights for player performance and injury risk.

---

## Project Structure
```
├── data/                         
│   ├── summary.csv                # Player-session mapping and metadata
│   └── football.duckdb            # Database
│
├── main.ipynb                   # Jupyter notebooks to reproduce analysis
│       
├── init.py                          # Initialization script
│
├── README.md                      # Project overview and instructions
└── LICENSE                        # GNU General Public License v3
```

---

## Requirements:
-Python 3.11.0 (for Jupyter Notebook analysis)  

---

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-directory>
```

2. Run init.py:

```bash
python init.py
```
---

3. Prepare the data folder:  
* Create a folder named data in the project directory.
* Place football.duckdb and summary.csv inside the data folder.

## Launch :
Run main.ipynb. The full workflow takes less than 10 minutes to complete.
---
## Licence :

This project is free software: you can redistribute and/or modify it under the terms of the GNU GPL v3.
No warranty is provided; see LICENSE for details.
