---
## Interactive Visualization of NTSB Aviation Accident Data 
##### Data timeline: 1962 – 2025
---
GitHub Pages link: https://michaeljevan.github.io/CIS_568_Final_Project/

---

  - **Michael J Evan**
  - **CIS-568 Data Visualization: Final Project**
  - **Graduate Computer Science Department**
  - **University of Massachusetts Dartmouth**
  - **Spring 2026**
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
- Popups provide direct link via record number to NTSB Accident information docket (available 2009 and later)

### Filters
- **Year range** — dual-handle slider (1962–2025) with numeric input fields and decade shortcut buttons (60s, 70s, 80s, 90s, 00s, 10s, 20s, ALL)
- **Injury severity** — Fatal, Serious, Minor, None, Unknown (drives dot colors on the map)
- **Weather conditions**
- **Engine configuration**
- **Aircraft type**
- **Purpose of flight**
- **FAR Part** (regulatory category)
- **Multi-Aircraft-Only** (override toggle for air-to-air or ground accidents)
- **Reset Filters** and **Reset Map** buttons

### Timeline Animation
- Year-by-year playback of accident data with play/pause control
- Visual progression of events across the map over time

### Additional
- **Analytics drawer** — charts and breakdowns of the filtered dataset
- **Documentation drawer** — in-app project documentation
- **Help & Info drawer** — usage tips and interface guide
- Retro-futuristic cyan-on-dark interface styled with Orbitron and Share Tech Mono typefaces
- Built on vanilla JavaScript, Leaflet, D3.js, and noUiSlider — no build step required

---
##### **Post for Academic Review**
##### *Note: best user interaction experienced on widescreen monitor*
---

### Project Interaction Instructions
#### HELP & INFO
#### MAP CONTROLS:

- Click any dot or cluster to open the accident popup
- Click the NTSB case number in the popup to open the full investigation docket on the NTSB
website. Information generally available 2009 and later.

#### CLUSTER groups nearby accidents -zoom in to separate them. Large datasets may render slowly
#### HEATMAP shows accident density weighted by injury severity
#### ALL DOTS plots every individual accident
### FILTERS:

- Single click any filter button to toggle on/of
- Double-click to isolate that category -hides all others
- Double-click again to restore all in that group
- Year range slider filters by accident date
- Injury level buttons in the top legend control dot colors on the map

### BASEMAP:

- DARK/STREET: switches between dark map (zoomed out) and street map (zoomed in)
- SECTIONAL: overlays FAA VFR sectional charts -best at zoom 6–12
- Note: Sectional view automatically switches to ALL DOTS mode
- TOPOGRAPHIC: from outer zoom to street level topographic interactive map
- SPIKE: interactive US spike map with hover over statistics. Click on state to open state/county hover over map

### TIMELINE ... Animates accidents year by year from 1962 to 2025
- Press ▶ to play, ✕ to close and return to your previous view
- Stats update in real time as the timeline advances
- Timeline works at any zoom level.

---

