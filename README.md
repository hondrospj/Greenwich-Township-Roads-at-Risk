# Greenwich Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Greenwich Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01413038, Greenwich
- PETSS / NOAA station: 8537374
- NAVD88 thresholds: 3.96 ft minor, 4.96 ft moderate, 5.96 ft major
- MLLW thresholds: 7.2 ft minor, 8.2 ft moderate, 9.2 ft major
- MLLW = NAVD88 + 3.24 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Greenwich Township boundary at 6.3-foot adaptive resolution.
