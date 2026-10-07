## Prathmesh Sonvane

M.Tech Water Resources and Environmental Engineering, Indian Institute of Science, Bengaluru. Graduating 2027.

I build satellite data systems for water and climate risk, and ship them as working software rather than notebooks.

Right now I am working on satellite augmented rating curve analysis for flood discharge estimation, quantifying how far discharge is misstated when a rating curve is assumed stable, and extending it to NASA SWOT radar interferometry so rating shift can be tracked at reaches with no gauge.

### Selected work

**[Flood extent mapping from radar satellite](https://github.com/prathmeshsonvane4-cloud/ClimateRisk-AI)**

Mapped 463 km2 of flood extent during the June 2022 Assam floods from Sentinel-1 SAR, at a point when cloud cover left optical imagery unusable. Speckle filtering, before and during change detection, permanent water removal with JRC Global Surface Water, terrain filtering with SRTM. Delivered as GeoTIFF and GeoJSON, ready for downstream exposure and damage assessment.

**[Stochastic streamflow modelling, Godavari basin](https://github.com/prathmeshsonvane4-cloud/stochastic-hydrology-godavari)**

Four decades of daily streamflow from catchment 3005 (Ashti), Maharashtra. ARMA(1,1) model and synthetic generator, validated with residual white noise tests. The honest limitation is that none of the models capture the monsoon extremes, which is the part that matters most for flood and reservoir planning.

**[AmeriFlux tower data analysis](https://github.com/prathmeshsonvane4-cloud/Ameriflux-tower-data-analyasis)**

Energy balance closure at the Ozark site and dry versus wet diurnal flux partitioning at Sevilleta, across five contrasting US ecoregions.

### Not public

**Kshetra** is a satellite crop and water intelligence platform for agricultural lending. Two services run on it: a farmer climate intelligence report built from multi year vegetation, water and rainfall trends, and village scale water balance and recharge stress analysis organised by water year.

It is running with a district cooperative bank in Latur, and across 141 village catchments in Maski taluka, Raichur.

The repository is private because the work is commercial. Happy to walk through the architecture and the hydrology engine on a call.

### Tools

Python, SQL, MATLAB, TypeScript

Google Earth Engine, Sentinel-1 SAR, Sentinel-2, MODIS, SMAP, ERA5-Land, CHIRPS, SRTM

scikit-learn, XGBoost, pandas, GeoPandas, QGIS, ArcGIS

FastAPI, PostgreSQL, PostGIS, Docker, Next.js

HEC-RAS, HEC-HMS

### Contact

[LinkedIn](https://www.linkedin.com/in/prathmesh-sonvane-759845259) and prathmeshs@iisc.ac.in
