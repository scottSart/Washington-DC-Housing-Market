# Real Estate Inventory Analysis

This repo processes and visualizes real estate data from Zillow and Apartment List. It cleans the data, calculates percentage changes, and generates several visualizations saved into dedicated folders.

## Features

- **Data Acquisition:** Downloads Zillow CSVs for new listings and on-market inventory; reads local rent data.
- **Data Processing:** Cleans, pivots, and calculates week-over-week/month-over-month percentage changes.
- **Visualizations:** Creates box plots, heatmaps, bar charts, density plots, and time-series line graphs for both new and total inventory.

## Setup

1. **Install Dependencies:**

   ```bash
   pip install pandas numpy matplotlib seaborn requests
2. Setup
* Clone the repo.
* Place Apartment_List_Rent_Growth_MoM_2025_02.csv in the repo root.
3. Running the Code
* Simply run the main analysis script. It will:
4. Create subdirectories: New Inventory on Market and Total Inventory on Market
* Pull data from Zillow and local CSV
* Clean, pivot, and compute percentage changes
* Generate and save visualizations in the corresponding directories
5. Data Sources
* Zillow new listings (monthly & weekly)
* Zillow for sale inventory (weekly)
* Apartment List rental data (local CSV)


