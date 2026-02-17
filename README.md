# Urban Ecosystem Enhancement through Rooftop Gardening:
## A GIS-Based Mapping Approach for Dhaka City

**Study Area:** Dhaka City, Bangladesh  
**Tools:** QGIS 3.44, Python (GeoPandas, Pandas), OpenStreetMap  

---

## Project Overview
Dhaka City has experienced rapid and largely unplanned urban expansion, resulting in high population density, land-use transformation, and severe pressure on urban ecosystems. The scarcity of open green spaces has intensified environmental challenges such as urban heat island effects, air pollution, and biodiversity loss.

Rooftop gardening offers a nature-based solution by utilizing underused rooftop surfaces to enhance urban ecosystem services. This project presents a GIS-based spatial assessment to identify and evaluate buildings suitable for rooftop gardening across Dhaka City.

---

## Methodology
- Building footprint data were obtained from OpenStreetMap  
- Administrative boundaries were used to spatially clip buildings within Dhaka City  
- Rooftop surface areas were calculated using GIS geometry functions in QGIS  
- A proportion of rooftop area was assumed to be gardenable, considering urban constraints such as accessibility and existing infrastructure  
- Python-based analysis using GeoPandas and Pandas classified buildings into:
  - Low suitability  
  - Medium suitability  
  - High suitability  

---

## Key Outputs
Total Estimated Rooftop Garden Area:
Using GeoPandas geometry calculations, the rooftop surface area of all buildings within Dhaka City was computed.
To reflect real-world feasibility, 30% of each rooftop area was assumed to be gardenable, accounting for:
- Water tanks and rooftop infrastructure
- Solar panels and utilities
- Access pathways and safety space
- Structural and load limitations

After applying this realistic constraint:
Estimated total rooftop garden area in Dhaka:
31,420,375 m²

This equals approximately:
- 31.4 km² of potential new urban green space
- Equivalent to over 4,400 football fields
- A significant opportunity for climate adaptation and urban greening
---
Suitability Classification
Buildings were grouped into three suitability categories based on available gardenable rooftop area:
| Suitability Level      | Description                                          |
| ---------------------- | ---------------------------------------------------- |
| **High suitability**   | Large rooftops with high gardening potential         |
| **Medium suitability** | Moderate rooftop area suitable for partial gardening |
| **Low suitability**    | Small rooftops with limited gardening potential      |

Spatial Insights
The analysis revealed:
- High suitability buildings are concentrated in planned residential and commercial zones
- Dense informal areas show lower rooftop gardening potential
- Even moderate adoption could substantially increase urban green coverage

## Applications
The analysis supports urban environmental management by:
- Informing green infrastructure planning  
- Supporting urban heat island mitigation strategies  
- Enhancing ecosystem services in dense urban environments  

---

## Technologies Used
- QGIS (Spatial analysis and mapping)  
- Python (GeoPandas, Pandas)  
- OpenStreetMap data  

---

## Repository Structure
data/ – Processed spatial datasets (Dhaka boundary, buildings, suitability layers)
notebooks/ – Python (GeoPandas, Pandas) analysis notebook
maps/ – Final GIS map outputs and visualizations

## Final Map Output

![Dhaka Rooftop Suitability Map](dhaka_rooftop_suitability_map.png)

