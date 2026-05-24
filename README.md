<div align="center">

# 🛰️ ORÁCULO SAT

### A global satellite analysis station — built entirely in the browser, with free and open data.

*Explore any point on Earth: satellite imagery, historical context, and computer vision in one place.*

`100% browser` · `free APIs` · `no cost` · `no servers`

**[Español](./README.es.md)** · English

</div>

---

## What is this?

**ORÁCULO SAT** turns any point on the planet into a research dossier. Click anywhere on the map and it instantly gathers what's there, whether it has been explored, real photos of the location, and historical context — then lets you enhance the satellite image, detect anomalies, compare years, lift the terrain into 3D, and ask an AI for a second opinion.

Everything runs **100% in your browser**. Nothing is uploaded to any server. It uses only **free and open data sources** with global coverage. Technology that cost millions a decade ago — now free for anyone with curiosity.

> Built from a phone, between lullabies, with AI as a copilot.

---

## ✨ Scope & Features

| Capability | What it does |
|------------|--------------|
| 🌎 **Point intelligence** | Wikipedia, OpenStreetMap, real geolocated photos, and exploration indicators for any coordinate worldwide |
| 🗂️ **Spectral enhancement** | Auto-contrast (CLAHE), false color, water/moisture index, edge detection, anomaly maps |
| 🧠 **AI detection** | Object detection running in-browser (TensorFlow.js) |
| 🕐 **Temporal analysis** | Compare the same area across years (2019–2025) to spot what stays permanent — a ruin, a wreck, a structure |
| ⛰️ **3D terrain + sun** | Real elevation (DEM) with adjustable sun angle; raking shadows reveal mounds, terraces, and buried structures |
| 🌊 **Marine bathymetry** | Sea-depth readout: is a wreck reachable or abyssal? |
| 📐 **Measure & compare** | Distances, areas, and a draggable before/after curtain |
| 🔮 **AI second opinion** | Claude interprets the analyzed image and suggests what to investigate |
| 💾 **Save & export** | Saved points, project export (`.json`), and Google Earth export (`.kml`) |

---

## 🧰 Tech Stack

Built entirely with open data and client-side libraries:

- **Satellite & imagery** — Sentinel-2 (ESA), Copernicus, EOX cloudless mosaics, Esri World Imagery
- **Open data** — OpenStreetMap (Overpass), Wikipedia (GeoSearch), Wikimedia Commons, Nominatim
- **Elevation & depth** — open elevation tiles (Terrarium), GEBCO bathymetry
- **Computer vision & 3D** — OpenCV.js, TensorFlow.js (COCO-SSD), three.js, Leaflet

No build step. No backend. A single HTML file.

---

## 🚀 Tutorial — Getting Started

### Run it
1. Download `oraculo-sat.html`.
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari).
3. That's it — no install, no account, no key required.

> **Note:** the *AI second opinion* feature needs an Anthropic API key when running the file standalone. Paste yours in the **API Configuration** panel (optional — every other feature works without it).

### Your first investigation
1. **Pick a point** — click anywhere on the map, or search a place by name.
2. **Read the intel** — the right panel fills with history, photos, catalogued sites, and (over water) depth.
3. **Capture & analyze** — hit *Capture area*, then try enhancement and detection tools.
4. **Go temporal** — enable the *timeline* and run *change detection*: red = changed, gray = permanent (your candidate).
5. **Lift it to 3D** — open *3D terrain*, crank **vertical exaggeration**, and slide the **sun hour** to dawn/dusk so raking shadows expose relief.
6. **Save your find** — name the point, write notes, then export a **dossier**, the **project**, or a **`.kml`** for Google Earth.

### Honest limitations
Free satellite imagery is ~10 m/pixel and elevation ~30 m. ORÁCULO SAT detects **candidates and large anomalies**, not small objects. It's a powerful **first filter** — not magic. Confirmation still needs sonar, drones, or fieldwork (and the proper permits).

---

## 📬 Contact

**Max Sarlija**
- ✉️ [hello@maxsarlija.com](mailto:hello@maxsarlija.com)
- 💼 [linkedin.com/in/msarlija](https://ar.linkedin.com/in/msarlija/es)

---

<div align="center">

*Made with open code, free data, and a lot of cold coffee.* ☕🛰️

**Powered by Max Sarlija**

</div>
