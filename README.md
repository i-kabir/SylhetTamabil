# Sylhet Tamabil Road Improvement Project

An interactive GIS map and structure management viewer for the Sylhet-Tamabil Road Improvement Project.

## 🌐 Live Webpage
The interactive viewer is published via GitHub Pages:
👉 **[https://i-kabir.github.io/SylhetTamabil/](https://i-kabir.github.io/SylhetTamabil/)**

---

## 🚀 Features
- **Interactive GIS Map**: Powered by Leaflet, displaying high-resolution satellite imagery and OpenStreetMap layers.
- **Multiple Alignment Overlays**:
  - Existing Road (`existing_road.geojson`)
  - Contract Alignment (`contract.geojson`)
  - Detail Design Alignment (`detail_design.geojson`)
  - Redesign Alignment (`redesign.geojson`)
- **Structure Inventory**: Interactive markers clustered along the alignment, loaded dynamically from `structures.csv`.
- **Filtering & Search**: Filter structures by type, group, or keyword search.
- **Document Integration & Export**: Embedded document previews and export filtered datasets directly to CSV.

---

## 📂 Repository Contents
| File | Description |
| :--- | :--- |
| `index.html` | Core web application with Leaflet mapping, sidebar panel, and interactive controls |
| `structures.csv` | Inventory dataset of structures (ID, type, coordinates, attached documents) |
| `existing_road.geojson` | GeoJSON features of the existing road alignment |
| `contract.geojson` | GeoJSON alignment for the contract design |
| `detail_design.geojson` | GeoJSON alignment for the detailed design |
| `redesign.geojson` | GeoJSON alignment for the redesign |
| `structures_arrangement.md` | Schema documentation for structure table headers |
