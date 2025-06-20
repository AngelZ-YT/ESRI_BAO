# 🗺️ Esri Enrichment Tool (Beta)

A script-based tool for conducting spatial enrichment using ArcGIS API for Python. Built to automate and scale data pulls for business and spatial analysis use cases.

---

## 📍 Background

[Esri Business Analyst Online (BAO)](https://bao.arcgis.com/esriBAO/index.html) is a web platform that provides business and demographic data for selected geographies. While powerful, BAO has key limitations:

- ❌ Manual, one-at-a-time processing
- ❌ High Esri Credit cost at scale
- ❌ Tedious export/import workflows

This tool solves those challenges through **automated Python scripting**, enabling **batch enrichment** of multiple locations at once using the **ArcGIS API for Python**.

---

## 🧪 Features

- ✅ Fully automated batch processing
- ✅ Customizable variable list and shapefile input
- ✅ Enriched Output both 'shapefile' and `.xlsx` for next-step analysis
- ✅ Python scripts included

---

## 📁 How It Works

### 🔢 Inputs:
- A list of enrichment variables (manually selected from esri database)
- A shapefile or feature collection of target geography

### 📤 Output:
- Enriched `.xlsx` and '.shp' with selected variables

---

## 🧠 Best Practices

- Ideal for batch enrichment across 10–100+ locations.
- Ensure your Esri API key has valid credits and access.

### ⚠️ Notes:

- **Credit Cost:** 1,000 data variables = 10 credits  
  Example: 20 locations × 100 variables = 20 credits
- **Service Limits:** Max 100 study areas per API request
- **Data Availability:** Only current year from ESRI estimate, and latest ACS 5-year, 2010, 2020 from Census
- **Results May Vary:** BAO reports vs. API output may differ slightly because of the polygons tolerance

---

## 🚀 Get Started

1. Clone or download the repo.
2. Open the Python script.
3. Update input paths and API key.
4. Run the enrichment script.
5. Review output `.xlsx` in the `Output` folder.

---

