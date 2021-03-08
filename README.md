# Land Cover Classification

### **External packages in the VENV:**

####**`REQUIRED:`**

- numpy
- pandas (version 0.24 or later)
- shapely (interface to GEOS)
- fiona (interface to GDAL)
- pyproj (interface to PROJ; version 2.2.0 or later)
- geopandas
- matplotlib (>= 2.2.0)
- mapclassify (>= 2.2.0)
- eo-learn

####**`OPTIONAL:`**

- rtree (optional; spatial index to improve performance and required for overlay operations; interface to libspatialindex)
- psycopg2 (optional; for PostGIS connection)
- GeoAlchemy2 (optional; for writing to PostGIS)
- geopy (optional; for geocoding)

###**Data source:**
GID (Gaofen-2) fine-labelled (15 labels) dataset: https://x-ytong.github.io/project/GID.html

