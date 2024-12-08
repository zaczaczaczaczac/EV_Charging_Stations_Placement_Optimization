# EV Charging Station Placement Optimization in Montreal

This project optimizes the placement of EV charging stations in Montreal using bio-inspired Genetic Algorithms (GAs). The objective is to minimize deployment costs while meeting traffic demand and station capacity constraints.

## Features
- **Optimization Methods**: Implements Standard GA, Modified GA (with elitism), and Adaptive GA (dynamic parameter adjustment).
- **Cost Minimization**: Balances deployment, service, and penalty costs.
- **Interactive Visualizations**: Provides maps and plots to analyze optimized station placements.

## Setup

### Prerequisites
- Python 3.8+
- Required Libraries: 
  - `pandas`
  - `numpy`
  - `folium`
  - `geopandas`
  - `osmnx`
  - `networkx`
  - `matplotlib`
  - `geopy`

### Installation
Install the required libraries using pip:
```bash
pip install pandas numpy folium geopandas osmnx networkx matplotlib geopy
