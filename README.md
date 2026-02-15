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
- Rooftop gardening suitability map for Dhaka City  
- Estimated total potential rooftop garden area  
- Spatial identification of priority areas for urban ecosystem enhancement  

---

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

![Dhaka Rooftop Suitability Map](maps/dhaka_rooftop_suitability_map.png)
