# resilience_tool
**Resilience Mapping Tool for Urban Hazards in Hyderabad** visualizes flood-prone and heat-vulnerable zones using real spatial datasets. Built with Python, GeoPandas, and Folium, it helps identify at-risk areas and supports climate-resilient urban planning.
# 🌆 Resilience Mapping Tool for Urban Hazards – Hyderabad (Dummy Data)

Using sample dummy spatial data, this project visualizes **flood-prone** and **heat-vulnerable** zones in **Hyderabad**, India. It serves as a prototype for building real-world urban resilience dashboards with Python.

---

## 📌 Project Overview

Climate change has increased the frequency and intensity of floods and heatwaves in urban areas. This tool demonstrates how to map and visualize such hazards for a city using Python and open geospatial libraries.

The current version uses **dummy polygon data** to simulate flood zones and heat zones in Hyderabad. The architecture can easily be extended with real datasets.

---

## 🎯 Objectives

- Plot the boundary of Hyderabad using OpenStreetMap.
- Overlay dummy polygons for:
  - 🌊 Flood-prone areas (blue)
  - ☀️ Heat stress zones (red)
- Create static and interactive hazard maps using GeoPandas and Folium.

---

## 🗃️ Folder Structure

resilience_mapping/
├── data/ # Contains dummy or future real datasets
├── notebooks/
│ └── resilience_tool.ipynb
├── requirements.txt
└── README.md

yaml
Copy
Edit


---

## 🧪 Libraries Used

- `geopandas` – for geospatial vector data
- `folium` – interactive map generation
- `matplotlib` – static map visualization
- `contextily` – basemaps for static maps
- `shapely` – geometric shapes for dummy hazard zones
- `osmnx` – to download city boundary from OpenStreetMap

---

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone https://github.com/your-username/resilience-mapping-hyderabad.git
cd resilience-mapping-hyderabad

2. **Create a virtual environment (optional)**
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

3. **Install dependencies**
pip install -r requirements.txt

4. **Launch the notebook**
jupyter notebook notebooks/resilience_tool.ipynb

📈 Sample Output
✅ Static map with flood zones (blue polygons)

✅ Static map with heat zones (red polygons)

✅ Interactive map using Folium showing both hazards


✍️ Dummy Data Description
Flood Zones: Two arbitrary polygons representing hypothetical flooded areas.

Heat Zones: Two additional polygons showing areas affected by urban heat.

These are used only for demonstration and are not based on real measurements.

📌 Use Cases
Prototype for real hazard mapping tools

Practice for urban analytics projects

Educational tool for learning GeoPandas, Folium, and mapping libraries in Python



