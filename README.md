## Interactive Visualization of NTSB Aviation Accident Data 
##### Data timeline: 1962 - 2025

---
GitHub Pages link: https://michaeljevan.github.io/CIS_568_Final_Project/

---

  - **Michael J Evan**
  - **CIS-568 Data Visualization: Final Project**
  - **Graduate Computer Science Department**
  - **University of Massachusetts Dartmouth**
  - **Spring 2026**

##### *Post for Academic Review*
##### Note: best viewed on widescreen monitor

---
![screenshot](https://github.com/user-attachments/assets/9d3fbf37-3d13-48c6-843c-edab83497c91)

---

## Features

### Data
- 168,793 NTSB aviation accident records, 1962–2025
- Real-time statistics panel showing filtered vs. total events, fatal events, serious injuries, and total fatalities — updates instantly with every filter change

### Map Views
- **Four basemaps:** Dark/Street (auto-switches by zoom), Aeronautical Sectional charts, Topographic, and a 3D Spike choropleth with state-to-county drill-down
- **Three data rendering modes:**
  - **Cluster** — aggregated markers with counts, chunked rendering for performance at 168k points
  - **Heatmap** — density-based heat layer
  - **All Dots** — every individual accident rendered as a colored point
- Custom zoom controls and popups with accident details
- Popups provide direct link via record number to NTSB Accident information (available 2009 and later)

### Filters
- **Year range** — dual-handle slider (1962–2025) with numeric input fields and decade shortcut buttons (60s, 70s, 80s, 90s, 00s, 10s, 20s, ALL)
- **Injury severity** — Fatal, Serious, Minor, None, Unknown (drives dot colors on the map)
- **Weather conditions**
- **Engine configuration**
- **Aircraft type**
- **Purpose of flight**
- **FAR Part** (regulatory category)
- **Multi-Aircraft-Only** override toggle
- **Reset Filters** and **Reset Map** buttons

### Timeline Animation
- Year-by-year playback of accident data with play/pause control
- Visual progression of events across the map over time

### Additional
- **Analytics drawer** — charts and breakdowns of the filtered dataset
- **Documentation drawer** — in-app project documentation
- **Help & Info drawer** — usage tips and interface guide
- Retro-futuristic cyan-on-dark interface styled with Orbitron and Share Tech Mono typefaces
- Built on vanilla JavaScript, Leaflet, D3.js, and noUiSlider - no build step required

