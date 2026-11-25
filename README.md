# Project Feasibility & Ecosystem Sensitivity Tool

**Developed by Berexford Saylee Jallah**

A browser-based screening tool that places a project prototype at real size on satellite imagery, detects sensitive ecosystems (mangrove, wetland, open water, tree cover), scores the project's feasibility, generates adaptation scenarios that keep sensitive ecosystems untouched, and produces a full report with maps, a 3D view, charts and tables.

**Open the tool:** https://epagislr.github.io/project-feasibility-tool/

## What it does
1. **Project & prototype** – place the plan at real ground size; upload a land parcel (KML/KMZ, GeoJSON, zipped Shapefile) and the plan fits itself to it; drape a site-plan image; view a detailed 3D model.
2. **Area of interest** – around the footprint, drawn on the map, or uploaded.
3. **Ecosystems & data** – ESA WorldCover 10 m satellite land cover (incl. mangroves), OpenStreetMap features, terrain elevation; adjustable protection buffers; upload your own layers.
4. **Feasibility score** – weighted 0–100 score with red flags; weights are editable.
5. **Adaptation scenarios** – relocate/rotate, compact, or clip to buildable land.
6. **Report & export** – printable report (save as PDF), HTML, GeoJSON and CSV.

## Requirements
A modern browser (Chrome, Edge, Firefox) and an internet connection for map imagery and environmental data. All code is contained in `index.html`; it can also be used as a local file.

## Data sources
Esri World Imagery · ESA WorldCover 2021 (via Microsoft Planetary Computer) · OpenStreetMap (Overpass API) · Mapzen/AWS terrain tiles · Nominatim.

## Disclaimer
This is a desk-based screening tool, not an Environmental and Social Impact Assessment (ESIA). Results must be verified in the field and by the Environmental Protection Agency of Liberia.
