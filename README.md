# Sustainable-Data-Center-Expansion
Data To Impact Challenge hosted by UVA x LMI Solutions


### Ideas
1. Sustainable Data Center Expansion Planning Tool
   - Help city planners, local communities, and developers evaluate siting options for potential data centers via geospatial analysis of environment
   - Considers energy consumption, emissions, water usage etc. through forecasting or simulating upkeep and map areas details like labor market, regulations on zoning, etc. e.g. temporal CNN, xgboost, regression
   - Quick Analysis option that generates composite scores (suitable vs unsuitable site) based on geospatial data like proximity transmission lines, zoning rules, environmental sensitivity, etc.
   - Risk Analysis based on satellite images of wildfires and flash flood risk
2. CoolSense Tool
   - Model that detects inefficiencies in water or airflow to improve resource usage

Other factors to consider: Noise and Light Pollution, Property value changes, heat waste, cybersecurity, regulations, impact on society and transparency and trust, species endangerment, habitat loss, backup generators are often deisel, blackout risks, surveillance issues, traffic, electromagnetic interference, utilities collaboration, monopolization, supply chain strain, foreign land grabs, shared border resources, end-of-life considerations

### Considerations
Environmental and technical perspectives:
Using satellite imagery, visualization tools, or data analysis to track impacts on power grids, water use, or land availability.

Policy and planning perspectives:
Considering how local governments or federal agencies balance competing priorities when approving data center siting and expansion.

Social and cultural perspectives:
Examining community narratives, workforce implications, or equity concerns surrounding where and how data centers are built.

AI Workflow design:
Envisioning how AI tools might assist decision-makers, for example, by supporting land-use planners in regions like northern Virginia, where requests for new data centers collide with a complex mix of environmental and economic considerations.

### Packages
Core:
- pandas
- numpy
- sklearn
- tensorflow
- tensorflow probability for uncertainty modeling
- pyomo for optimization after having sklearn model
- geopandas
- shapely
- simpy for simulating equipment uptime and maintanenance
- plotly dash
- prefect for workflow management

Potential:
- xarray for high dimensional simulation data
- statsmodels if time series or simple model, no need for sklearn
- rasterio to read raster data e.g. elevation, climate, etc.
- pint for energy unit conversion
- coolprop for advanced thermal modeling
- RISE for notebook presentation

### Data Sources
- https://data.lib.vt.edu/articles/dataset/The_environmental_footprint_of_data_centers_in_the_United_States/14504913?utm_source=chatgpt.com
- https://eta-publications.lbl.gov/sites/default/files/2024-12/lbnl-2024-united-states-data-center-energy-usage-report.pdf?utm_source=chatgpt.com

### Resources

- Challenge Preview: [https://lmisolutions.com/challenges/Data-to-Impact]
- Challenge Info: [https://go.lmisolutions.com/challenges/2026]
- NREL Data Tools: [https://www.nrel.gov/research/data-tools]
- NREL Data: [https://data.nrel.gov/submissions]
- Example Planning Tool: [https://www.urbansim.com/]
- Urbanism Github: [https://udst.github.io/urbansim/gettingstarted.html]
