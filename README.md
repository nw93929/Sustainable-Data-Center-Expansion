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

Potential:
- xarray for high dimensional simulation data
- statsmodels if time series or simple model, no need for sklearn
- rasterio to read raster data e.g. elevation, climate, etc.
- pint for energy unit conversion
- coolprop for advanced thermal modeling

### Resources

- [https://lmisolutions.com/challenges/Data-to-Impact]
- [https://go.lmisolutions.com/challenges/2026]
- [https://www.nrel.gov/research/data-tools]
- [https://data.nrel.gov/submissions]
- [https://www.urbansim.com/]
