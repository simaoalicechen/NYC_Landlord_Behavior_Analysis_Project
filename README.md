# NYC Landlord Behavior Analysis Project

## Overview
This is an ongoing, semester-long data science project that explores landlord behavior in NYC using three primary datasets (additional datasets will be incorporated as research progresses):

- **Evictions dataset:** [Evictions data](https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4/data)
- **311 complaints dataset:** [311 complaints data](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9/about_data)
- **BBL dataset:** A unique identifier for NYC properties used to merge and cross-reference the datasets.
- **NYC Building Footprints:** "A polygon layer of counties in NYS listing sources of building footprint data and direct download links to individual county building footprint geodatabase." [NYC Building Footprints](https://data.gis.ny.gov/maps/a6bbc64e38f04c1c9dfa3c2399f536c4/about)

## Current objectives/groups of hypotheses
1. **Q1:** Analyze how property-related complaints and eviction rates correlate. [During Covid]
2. **Q2:** Identify landlords and patterns of landlord behavior based on building type, complaint frequency, and eviction trends of all cleaned data Q2.1: Plotly Q2.2: Folium
3. **Q3:** Identify buildings most prone to evictions and propose relevant questions about  the societal, policy, corporate, and economic influences behind those trends. Q3.1: analysis Q3.2: Folium viz
4. **Q4:** Identify neighborhoods most prone to evictions and propose relevant questions about  the societal, policy, corporate, and economic influences behind those trends.
5. **Q5:** Prepared and Re-aggregated the average eviction count by zip codes, boroughs, and neighborhoods, breaking the data into smaller CSV files for better integration with ArcGIS.
6. **Q6:** Use ArcGIS' geodata-processing functions, online datasets, and datasets mentioned above to create images and visual summaries (see Images folder).

## Project Structure
- **Cleaning notebooks** are separated from analysis notebooks to maintain clarity.
- **Exploratory Data Analysis (EDA)** of eviction data is broken into five parts for readability and easier file management in Git.
- Data analysis based on the defined research questions addresses the Q1, Q2, Q3, and Q4 hypotheses. More comprehensive conclusions will be drawn as additional data and non-data literature are included in future analyses.
- Use **Gaussian Neural Networks** to predict 2024 eviction data and compare and analyze the actual data.
- Make **ArcGIS integration** more seamless by generating and customizing different smaller-size CSVs.
- Images folder contains ArcGIS results that will be used to illustrate evictions at the neighborhood level.
