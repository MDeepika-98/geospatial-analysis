# 🚔 Crime Incidents in 2024

## 📄 Overview

This project focuses on the geospatial analysis of crime incidents reported in the District of Columbia for the year 2024. The dataset is sourced from the District of Columbia Metropolitan Police Department (MPD) and provides location-based details on various crime occurrences within the district. By examining this data, we aim to identify spatial patterns, crime hotspots, and trends that can inform public safety strategies and urban planning decisions.

## 📊 Dataset Details

* Source: District of Columbia Metropolitan Police Department (MPD)

* Dataset Link: [Crime Incidents in 2024](https://catalog.data.gov/dataset/crime-incidents-in-2024/resource/48eeb897-aa75-4d14-9f73-8765f6e7f93a?inner_span=True)

* Data Format: Available in multiple formats including CSV, Shapefile, GeoJSON, and KML.

## 📑 Geospatial Data Attributes

The dataset contains location-based attributes that enable geospatial analysis:

* X:
The X coordinate for the incident location based on the underlying spatial reference system.

* Y:
The Y coordinate for the incident location.

* CCN:
Crime Case Number – a unique identifier for each recorded incident.

* REPORT_DAT:
Date and time when the incident was reported. This includes time zone information.

* SHIFT:
The operational shift during which the incident occurred (e.g., DAY, EVENING, MIDNIGHT).

* METHOD:
The method or instrument associated with the incident (e.g., GUN, KNIFE, OTHERS).

* OFFENSE:
A more detailed description of the crime type, such as THEFT (with additional context like F/AUTO or OTHER) or HOMICIDE.

* BLOCK:
A descriptive label for the street block where the incident occurred (e.g., “1100 - 1199 BLOCK OF 18TH STREET NW”).

* XBLOCK & YBLOCK:
Coordinates corresponding to the block location, typically mirroring the primary X and Y values.

* WARD:
The ward or district number where the incident was recorded.

* ANC:
Advisory Neighborhood Commission designation, which provides additional local administrative context.

* DISTRICT:
A numerical value representing the broader jurisdictional district.

* PSA:
Public Safety Area code – an administrative designation used for resource allocation and reporting.

* NEIGHBORHOOD_CLUSTER:
A label that groups incidents by neighborhood clusters (e.g., Cluster 6, Cluster 5).

* BLOCK_GROUP:
A grouping code for blocks that often follows a local classification system.

* CENSUS_TRACT:
The census tract number, which can be used for demographic analysis.

* VOTING_PRECINCT:
The designated voting precinct area associated with the incident location.

* LATITUDE:
The latitude coordinate for mapping the incident.

* LONGITUDE:
The longitude coordinate for mapping the incident.

* BID:
A Business Improvement District or similar area identifier that may indicate a specific urban area (e.g., “GOLDEN TRIANGLE”, “DOWNTOWN”).

* START_DATE:
The starting time of the incident (if applicable).

* END_DATE:
The ending time of the incident (if applicable).

* OBJECTID:
An internal unique identifier for the record.

* OCTO_RECORD_ID:
This column was removed from the dataset because it did not contain any values.

## 🔍 Geospatial Analyses

Using this dataset, we focus on spatial analyses such as:

* Crime Hotspot Mapping: Identify high-crime areas using geospatial clustering techniques.

* Neighborhood Risk Analysis: Compare crime density across different wards and neighborhoods.

* Geospatial Temporal Trends: Analyze changes in crime patterns over time using GIS techniques.

* Proximity Analysis: Assess the impact of nearby locations (e.g., schools, public spaces) on crime incidents.

* Heatmaps and Spatial Visualization: Generate visual heatmaps of crime incidents to better understand spatial distribution.

## ⚠️ Data Considerations

* Geocoding Accuracy: Incident locations are geocoded to the District's Master Address Repository and mapped accordingly. Some discrepancies may exist.

* Data Updates: The dataset is updated periodically, and working with the most recent version ensures accurate geospatial analysis.

* Privacy Considerations: Specific addresses are generalized to protect individual privacy while maintaining spatial accuracy.

## 📥 Accessing the Data

The dataset is available in geospatial formats:

* Shapefile: For GIS applications like ArcGIS and QGIS.

* GeoJSON: Useful for web-based mapping and analysis.

* KML: Compatible with applications like Google Earth for visualization.

* CSV: Can be used for data analysis and converted into geospatial formats.

To download the dataset, visit [the Crime Incidents in 2024 page](https://catalog.data.gov/dataset/crime-incidents-in-2024/resource/48eeb897-aa75-4d14-9f73-8765f6e7f93a?inner_span=True) and select the appropriate format.

## 🤝 Contribution

We welcome contributions that enhance the geospatial analysis of crime incidents. If you have suggestions, improvements, or additional insights, please open an issue or submit a pull request.

###This README provides a foundational understanding of the geospatial analysis of crime incidents in the District of Columbia. Users are encouraged to explore the data further and apply GIS and spatial analytics to derive actionable insights.
