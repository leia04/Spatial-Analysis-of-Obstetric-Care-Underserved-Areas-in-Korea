# Spatial Analysis of Obstetric Care Underserved Areas in Korea

## Abstract
This project identifies obstetric care underserved areas by integrating spatial accessibility and actual childbirth demand.  
Unlike existing criteria that rely mainly on distance or utilization rates, this study defines demand using women aged 25–39, reflecting real childbirth patterns, and applies network-based Two-Step Floating Catchment Area (2SFCA) analysis to capture realistic accessibility to delivery facilities. The results reveal districts with high demand but insufficient access, highlighting limitations of current policy standards.

## Problem
- Rapid decline of obstetric delivery facilities in Korea
- Existing accessibility-based criteria may overlook areas with high childbirth demand
- Distance-based measures alone fail to reflect road-network constraints and spatial inequality

## Approach
- Demand: Women aged 25–39 (actual childbirth population)
- Supply: Hospitals equipped with delivery rooms
- Methods:
  - 20 km buffer-based accessibility analysis
  - Network-based 2SFCA using OpenStreetMap road networks

## Key Findings
- Jeollanam-do was identified as the most vulnerable province
- Nine districts showed zero accessibility under the 2SFCA framework
- Naju-si emerged as a critical case with high childbirth demand but an accessibility score of zero

These results suggest that policy interventions based solely on distance or utilization criteria may fail to detect high-risk underserved areas.

## Tools and Libraries
- Python
- Pandas, GeoPandas
- OSMnx, NetworkX
- Shapely, Matplotlib

## My Contribution
- Designed the demand definition based on childbirth statistics (women aged 25–39)
- Implemented the network-based 2SFCA accessibility analysis
- Performed spatial preprocessing and visualization
- Interpreted analytical results from a policy-oriented perspective
