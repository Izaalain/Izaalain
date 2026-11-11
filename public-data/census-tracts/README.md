# Pennsylvania census tract outlines

`pa-tracts-2025.geojson` contains 2025 census tract outlines for Cumberland,
Dauphin, Lancaster, Lebanon, Philadelphia, and York counties in Pennsylvania.
The file contains 787 features in WGS84 GeoJSON. Each feature has an 11-digit
string tract identifier in its `id`, `GEOID`, and `census_tract_geoid`.

The source is the U.S. Census Bureau's
[2025 Pennsylvania 1:500,000 cartographic boundary file](https://www2.census.gov/geo/tiger/GENZ2025/shp/cb_2025_42_tract_500k.zip).
The source was filtered by county and converted from NAD83 to WGS84 without
additional simplification. These boundaries are intended for visualization,
not precise surveying or authoritative geocoding.

After this file is committed and pushed to `main`, its raw URL is:

```text
https://raw.githubusercontent.com/Izaalain/Izaalain/main/public-data/census-tracts/pa-tracts-2025.geojson
```

The GeoJSON is manually copied from the air-quality project's processed
boundary artifact. Updates to that project do not automatically update this
file. A different Census vintage should use a separately versioned filename.
