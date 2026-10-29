# Optimal Site Selection for a New Health Center using QGIS

**Author:** Md Rimon Patwary  
*Incoming Master of Applied Science (Biodiversity Management) Student at Unitec Institute of Technology, New Zealand.*

## Overview
This portfolio project focuses on spatial suitability modeling to identify optimal locations for establishing a new health center in Bangladesh. By leveraging open-source geospatial data, the analysis evaluates proximity constraints and service gaps to support evidence-based infrastructure planning.

## Objectives
- Evaluate spatial factors affecting public access to healthcare facilities.
- Execute buffer and overlay analysis integrated with existing road networks and infrastructure layers.
- Visualize suitability tiers through high-quality, communicative cartographic outputs.

## Final Output Maps

### 1. District-wise Area Distribution Map of Bangladesh
This choropleth map illustrates the baseline administrative divisions and spatial area distribution across the 64 districts of Bangladesh.
![District-wise Area Distribution Map](maps/bangladesh_district_area_map.png)

### 2. Health Center Site Selection Map
This multi-criteria suitability map displays the final targeted buffer zones and optimized sites for the proposed health center.
![Health Center Site Selection Map](maps/health_center_site_selection.jpeg)

## Tools & Technologies
- **GIS Software:** QGIS
- **Analysis Modules:** Raster Calculator, Vector Proximity (Buffers), Overlay (Difference/Intersection)
- **Cartographic Output:** QGIS Print Layout

## Methodology
1. **Data Acquisition:** Sourced administrative boundaries and baseline infrastructure vectors (roads, places, points of interest, and buildings) from OpenStreetMap (OSM).
2. **Data Preprocessing:** Standardized coordinate reference systems (CRS) and projection values for accurate geometric measurements.
3. **Proximity & Overlay Modeling:** Applied multi-criteria buffer analysis followed by overlay and difference queries to isolate target locations.
4. **Cartographic Design:** Composed the final map outputs with essential cartographic elements including dynamic scale bars, legends, titles, and north arrows.

## Key Skills Demonstrated
QGIS | Spatial Analysis | Site Suitability Modeling | Cartographic Design | Open Data Integration

## Project Status
Completed as an independent GIS portfolio project.

## Connect
[LinkedIn](https://www.linkedin.com/in/md-rimon-patwary)
---
**Data Source:** Bangladesh Administrative Boundaries | OpenStreetMap (OSM). Map data © OpenStreetMap contributors.
