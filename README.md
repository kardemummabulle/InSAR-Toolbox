# InSAR-Toolbox

**InSAR-Toolbox** is an ArcGIS-native toolbox/add-in with a companion R package **`{insar}`** for working with **EGMS** (European Ground Motion Service) InSAR data **inside ArcGIS**. It was **inspired by** the QGIS plugin **InSAR Explorer** and aims to offer similar, streamlined workflows for the Esri ecosystem.

- **Data source:** European Ground Motion Service — https://egms.land.copernicus.eu/  
- **Inspiration:** QGIS *InSAR Explorer* — https://plugins.qgis.org/plugins/insar_explorer-dev/

## What it does
- **Download / import** EGMS data into ArcGIS.
- **Explore** deformation on the map with **per-point** and **group** time-series plots.
- **Analyze** with light **QC**, trend summaries, and **interpolation** (IDW/kriging) for screening surfaces.
- **Export** plots (PNG/SVG) and publish **time-enabled** layers for dashboards.

## Quick start (preview)
**ArcGIS Pro**
1. Install the *InSAR-Toolbox* add-in.  
2. Run **EGMS Download/Import** → create a time-enabled layer.  
3. Click a point to open its time-series plot; select an AOI to make a **group plot**.  
4. Export figures or publish a hosted, time-enabled layer.
