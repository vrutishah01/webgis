# 🌍 WebGIS Project – Isle of Wight Coastal & Risk Mapping

**AV Developers** is a GIS consulting firm established with a vision to explore advanced **web mapping technologies** and deliver practical web-based GIS solutions. This project is part of an academic prototype developed for the **Isle of Wight Council**, showcasing multiple approaches to modern web-GIS using real geospatial data.

🔗 **Live Project**: [webgis-steel.vercel.app](https://webgis-steel.vercel.app/)  

> _"Web GIS allows us to take our systems of record – our traditional server and desktop technologies – and integrate them, bringing them together into a system of systems."_  
> — **Jack Dangermond**

---

## 🧭 About the Project

This project demonstrates **four major web mapping approaches** applied to visualize environmental and infrastructure data for the Isle of Wight (IOW) region:

1. **ArcGIS Web AppBuilder** (No-code configuration)
2. **ArcGIS JavaScript API** (Interactive web maps)
3. **Leaflet with GeoServer (WMS integration)**
4. **Google Maps JavaScript API with KMZ data**

Each approach utilizes specific datasets such as roads, towns, rainfall grids, soil types, and flood risk zones to show a complete WebGIS experience.

---

## 🗂️ Geospatial Datasets Used

| Dataset                | Format | Description                                                                 |
|------------------------|--------|-----------------------------------------------------------------------------|
| `IOW_Coastal.kml/kmz`  | Line   | Coastal boundary of Isle of Wight                                           |
| `IOW_Coastal_Path.kml` | Line   | Hiking trails / walking paths on the coast                                 |
| `roads.kmz`            | Line   | Major road networks                                                         |
| `towns.kmz`            | Point  | Locations of towns across the island                                       |
| `floodrisk_towns`      | WMS    | Towns highly prone to flooding (via GeoServer)                             |
| `soilscapes, rainfall` | Raster/Grid | Soil drainage categories and average rainfall zones (in JS/ArcGIS map) |

---

## 🚀 Web Mapping Approaches

### 1️⃣ ArcGIS Web AppBuilder
- No-code platform used to create a map with interactive widgets.
- Layers: Towns, Roads, Soil types, Rainfall.
- Features: Pop-ups, attribute tables, search, legend, charts, and more.

### 2️⃣ ArcGIS JavaScript API
- Coded map using ESRI's JavaScript API.
- Shows heavy rainfall zones, soil drainage categories, and towns in affected areas.

### 3️⃣ Leaflet + GeoServer
- GeoServer used to serve WMS layers.
- Leaflet used for frontend mapping and interaction.
- Layers include flood risk towns and IOW coastal outline.

### 4️⃣ Google Maps + KMZ
- Uses Google Maps JS API to load `.kmz` files from GitHub.
- Displays major roads and other KML/KMZ vector overlays.
- KMZ hosted directly via GitHub raw URLs.

---

## 📊 Code Overview

- `kml_gm.html`: Uses Google Maps API to render `.kmz` roads and towns data.
- `leaflet_wms.html`: Leaflet map connecting to GeoServer's WMS services.
- `data/`: Contains local geospatial data used in the project (KMZ/KML).
- Code is modular, minimal, and easy to extend.

---

## ✅ Summary

This project showcases:
- Multiple WebGIS technologies
- Real-world datasets
- Hosted and deployed interactive maps
- A consulting-level prototype for decision-makers like local councils

---

🛠️ Built with passion for GIS & the web, by **Vruti Shah**.

### Thank you!
