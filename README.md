# Data Processing Project - Hong Kong Common Spatial Data

This project processes and extracts address data from the Hong Kong Common Spatial Data Infrastructure (CSDI). The dataset includes geographic and residential information across 18 districts, including public rental and private housing addresses. Source: CSDI Geoportal, Link: https://portal.csdi.gov.hk/geoportal/?lang=undefined&datasetId=dpo_rcd_1629267205232_33603

![alllogo2 tmb-ze-500-500](https://github.com/user-attachments/assets/25c01767-03bf-42e0-b2b5-e18402dbec5b)

## Overview
With the increasing demand for accessible data, this project utilizes open-source geographic information for data warehousing. By converting raw GeoJSON files into structured Excel (XLSX) format, the project simplifies the process of analyzing and manipulating complex spatial data.

## Features
1. Data Extraction: 
Efficiently reads and processes multiple GeoJSON files containing district-level address data.

2. Data Transformation: 
Converts nested GeoJSON structures into a flattened Excel format for easier integration.

3. Batch Processing: 
Automatically handles all 18 districts in a single run, standardizing 39 key columns (e.g., CSDI_BuildingID, CSDI_DistrictC).

4. Coordinate Mining: 
Automatically extracts and converts Longitude and Latitude (WGS84) from geometry objects into float values.

## Key Analytics Insights
Beyond the data conversion, this project provides three core insight:

1. District Statistical Summary: 
Ranked all 18 districts by address count, identifying Yuen Long as the district with the highest number of records.

2. Building Density Analysis: 
Identified high-density urban corridors and development hotspots through spatial point distribution.

3. Street Frequency Analysis: 
Extracted and identified the most prominent road networks in Hong Kong (e.g., Castle Peak Road, Tai Po Road).
