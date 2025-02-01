# Aspiring Spatial Data Scientist
 Welcome to my spatial data science portfolio!

I am passionate about using spatial data to solve real-world problems through GIS, remote sensing, and data analytics. My projects focus on urban planning, disaster mitigation, and socioeconomic analysis, showcasing my skills in Python, GEE JS API, and QGIS.

## Education
4th year BS Geodetic Engineering student, University of the Philippines

## Work Experience
* National Mapping and Resource Information Authority (NAMRIA) Intern
* UP Geop EngaGE Mapper

## Volunteer
* Ecosia Mapper
* OSM Mapper

## Projects

### 1. Handling Geospatial Data
#### Description
This code extracts OpenStreetMap (OSM) data to calculate building density for each municipality in Quezon City. It utilizes Python libraries such as osmnx and GeoPandas to fetch, process, and analyze spatial data. The workflow involves the following steps:

* **Data Extraction:** Retrieves building footprint data from OSM for the specified geographic boundaries.
* **Data Cleaning and Processing:** Filters and prepares the OSM data to ensure accuracy and completeness.
* **Building Density Calculation:** Computes building density (number of buildings per unit area) for each municipality.
* **Visualization:** Generates maps and statistics to present the spatial distribution of building densities.

This analysis supports urban planning initiatives by providing insights into building density patterns across Quezon City.

#### Dependencies
<img src="/images/pandas.png" alt="Alt text" width="300"> <img src="/images/numpy.png" alt="Alt text" width="300"> <img src="/images/geopandas_logo.png" alt="Alt text" width="250">


#### Sample Output
<img src="/images/densitymap.png" alt="Alt text" width="500">

#### Link to Project: [GE 197: Exercise 1 - Handling Geospatial Data](https://colab.research.google.com/drive/10_zOpsQ1UPAgxYwMC4vzFUI-VobPIBjD?usp=sharing)
    

### 2. Spatial Statistics on TripAdvisor

#### Description
Performed spatial statistical analysis to examine housing price patterns across Metro Manila. Utilized tools like GeoPandas and PySAL to explore spatial autocorrelation and clustering.
* **Data Extraction:** Collected housing price data and spatial boundaries.
* **Data Cleaning and Processing:** Preprocessed and cleaned the data using GeoPandas.
* **Spatial Autocorrelation:** Analyzed spatial autocorrelation (Moran's I) to identify clustering patterns.
* **Spatial Regression:** Implemented spatial regression analysis to model the variables.
* **Visualization:** Mapped and visualized results to highlight housing price trends.

#### Dependencies
<img src="/images/pandas.png" alt="Alt text" width="300"> <img src="/images/numpy.png" alt="Alt text" width="300"> 
<img src="/images/netx.png" alt="Alt text" width="300"> <img src="/images/geopandas_logo.png" alt="Alt text" width="250"> 
#### Sample Outputs
<img src="/images/corr.png" alt="Alt text" width="700">

#### Link to Project: [GE 197: Exercise 2 - Spatial Statistics on TripAdvisor Data](https://colab.research.google.com/drive/1R9CaRlqx5I4FenRY3xdEiOuz5n2sD4A0?usp=sharing)

### 3. Accessibility and Centrality Analysis (Team)

#### Description 
This code analyzes and visualizes travel times to universities in urban cities under normal and disrupted road conditions using isochrone mapping and centrality analysis.
* **Data Collection:** Collected road network and university location data for Quezon City and Manila City.
* **Isochrone Mapping:** Used isochrone maps to illustrate ideal and actual travel times before and after road disruptions.
* **Centrality Analysis:** Performed centrality analysis to identify critical road segments impacting travel times.
* **Visualization:** Visualized findings to highlight travel accessibility challenges and opportunities for improvement.
#### Dependencies
<img src="/images/pandas.png" alt="Alt text" width="300"> <img src="/images/numpy.png" alt="Alt text" width="300"> 
<img src="/images/netx.png" alt="Alt text" width="300"> <img src="/images/geopandas_logo.png" alt="Alt text" width="250"> 

#### Sample Outputs
<img src="/images/isochroneMM.jpg" alt="Alt text" width="500"> <img src="/images/IsochroneMMwithinterruptions.jpg" alt="Alt text" width="500"> 
<img src="/images/isochroneQC.jpg" alt="Alt text" width="500"> <img src="/images/IsochroneQCwithinterruptions.jpg" alt="Alt text" width="500"> 


#### Link to Project: [GE 197: Capstone Project - Byaheng Late: Evaluating University Accessibility and Road Disruption using Isochrone and Centrality Analysis](https://colab.research.google.com/drive/1XcDv72xO9irIfRpr47ivaLLsaMxXEBOt?usp=sharing)

### 4. Nighttime Light and Carbon Monoxide Modeling

#### Description
This script models the relationship between Nighttime Light (NTL) and Carbon Monoxide (CO) levels in Metro Manila, Philippines. The goal of the analysis is to understand the correlation between urban development, human activity, and pollution levels, particularly focusing on how these variables reflect urbanization patterns and environmental health.
* **Collect and Filter Data:** Gather NTL (VIIRS) and CO data for Metro Manila and filter by relevant time periods.
* **Preprocess Data:** Apply quality filtering and normalize the data for comparison.
* **Analyze Correlation:** Perform analysis to assess the relationship between NTL and CO levels.
* **Visualize Results:** Generate maps and time-series plots to display findings.
* **Interpret Findings:** Analyze the correlation between human activity and pollution.


#### Dependency
<img src="/images/gee.png" alt="Alt text" width="250"> 

#### Link to Project: [Google Earth Engine Projects](https://code.earthengine.google.com/?accept_repo=users/cspaliza/GsE_189)

<iframe width="800" height="450" 
    src="https://www.youtube.com/embed/jixRGMtnpu0" 
    frameborder="0" allowfullscreen>
</iframe>

