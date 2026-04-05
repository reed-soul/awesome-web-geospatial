# Changelog - Awesome Web Geospatial

## Changes Made: Removed Unrelated, Enriched with Relevant

### 🗑️ REMOVED: Too Far from Web-Specific Geospatial

#### Desktop/Backend Tools (Not Web Development)
- ❌ **QGIS Cloud** - Web publishing platform for QGIS desktop, not a developer library
- ❌ **Google Earth Engine** - Proprietary cloud computation platform (heavy lifting on Google servers)
- ❌ **QGIS Tutorials** - Desktop GIS tutorials (Python), not web development
- ❌ **GeoPython Tutorials** - Python for geospatial, not JavaScript/web

#### General-Purpose Tools (Not Geospatial-Specific)
- ❌ **Plotly.js** - General scientific charting library (maps are one of dozens of chart types)
- ❌ **3d-force-graph** - General 3D graph visualization (geospatial layout is one mode)
- ❌ **jVectorMap** - SVG-based map library, unmaintained, domain expired, not geospatial-specific
- ❌ **geometric.js** - Abstract 2D computational geometry, no CRS/earth awareness
- ❌ **flatten-js** - Abstract 2D geometry, no geospatial context

#### Platforms (Not Developer Libraries)
- ❌ **OpenStreetCam / KartaView** - Street imagery data collection platforms, not SDKs
- ❌ **OpenSphere** - Complete end-user GIS web application (by NGA), not a library

#### Defunct/Redundant
- ❌ **Stamen Design** - Absorbed into Stadia Maps (already listed) since October 2023

#### Incorrect Entry
- ❌ **S2 Geometry** - Listed C++ repo, not the JS port. Removed for clarity.

**Total removed: 13 items**

---

### ✨ ADDED: Genuinely Relevant Web Geospatial Tools

#### Core Mapping
- ✅ **Google Maps JavaScript API** - Google's web mapping API with Street View, places, routing

#### Vector Tiles & Data Formats
- ✅ **shpjs** - Parse Shapefiles in browser, returns GeoJSON projected to WGS84

#### Spatial Indexing
- ✅ **kdbush** - Static spatial index for 2D points (by Vladimir Agafonkin)
- ✅ **geokdbush** - Geographic extension for KDBush, fast nearest-neighbor for Earth locations
- ✅ **tinyqueue** - Priority queue / heap for pathfinding algorithms (Dijkstra/A*)

#### Framework-Specific Components
- ✅ **@mapcomponents/react-maplibre** - Declarative React GIS components for MapLibre
- ✅ **@maplibre/ngx-maplibre-gl** - Official Angular binding for MapLibre GL JS

#### Geocoding & Routing
- ✅ **leaflet-control-geocoder** - Leaflet geocoder with Nominatim, Photon, Pelias, Bing, Mapbox support
- ✅ **Leaflet Routing Machine** - Multi-backend routing control (OSRM, Mapbox, GraphHopper, Valhalla)
- ✅ **MapLibre GL Directions** - Official MapLibre routing directions plugin
- ✅ **@graphhopper/directions-api-js-client** - JavaScript client for GraphHopper API

#### Map Controls & UI Components **[NEW CATEGORY]**
- ✅ **leaflet.locatecontrol** - Geolocation control (used by osm.org, mapbox)
- ✅ **maplibre-gl-compass** - Heading-up compass for MapLibre
- ✅ **Leaflet.Control.Opacity** - Opacity sliders for tile layers
- ✅ **Leaflet.StyledLayerControl** - Advanced layer control with grouping
- ✅ **maplibre-gl-layer-control** - Layer control with show/hide, opacity, legends
- ✅ **map-gl-style-switcher** - Style switcher for Mapbox/MapLibre
- ✅ **leaflet-minimap** - Minimap showing viewport position
- ✅ **leaflet.fullscreen** - Fullscreen button using Fullscreen API
- ✅ **Leaflet.MousePosition** - Mouse coordinate display
- ✅ **leaflet-hash** - URL hashes for bookmarking/sharing map views
- ✅ **leaflet-areaselect** - Bounding box selection overlay
- ✅ **sidebar-v2** - Collapsible sidebar for Leaflet

#### Map Measurement & Editing Tools **[NEW CATEGORY]**
- ✅ **leaflet-measure** - Coordinate, linear, and area measurement
- ✅ **Leaflet.Measure** - Distance and area measurement control
- ✅ **leaflet-measure-path** - Shows measurements on drawn paths
- ✅ **@raruto/leaflet-elevation** - Elevation profiles with d3.js (GPX, GeoJSON, KML)

#### Map Animation & Time Dimension **[NEW CATEGORY]**
- ✅ **Leaflet.TimeDimension** - Time dimension for Leaflet (weather, oceanographic data)
- ✅ **maplibre-transition** - Smooth transitions between map styles
- ✅ **leaflet-velocity** - Wind fields, ocean currents with particle animation

#### Map Printing & Export **[NEW CATEGORY]**
- ✅ **leaflet-easyprint** - Print/export for Leaflet maps
- ✅ **leaflet-image** - Export Leaflet maps to images client-side
- ✅ **leaflet-simple-map-screenshoter** - Promise-based screenshot for Leaflet
- ✅ **maplibre-gl-video-export** - Video export for MapLibre (WebM/MP4 with animations)

#### Offline Maps & Caching **[NEW CATEGORY]**
- ✅ **leaflet.tilelayer.pouchdbcached** - Tile caching to PouchDB for offline use
- ✅ **protomaps-leaflet** - Offline maps with PMTiles format in Leaflet

#### Plugins & Extensions
- ✅ **leaflet.wms** - Full-featured WMS plugin for Leaflet (single-tile, tiled, GetFeatureInfo)
- ✅ **maplibre-gl-leaflet** - Bridge allowing MapLibre layers inside Leaflet
- ✅ **Threebox** - Three.js integration for 3D models in Mapbox/MapLibre

#### Style Specification & Validation **[NEW CATEGORY]**
- ✅ **@maplibre/maplibre-gl-style-spec** - MapLibre Style Specification utilities

#### Learning Resources
- ✅ **Made with MapLibre** - Showcase of MapLibre projects and tutorials
- ✅ **MapLibre Discord** - MapLibre community chat

**Total added: ~40 items across 5 new categories**

---

### 📊 Summary Statistics

| Metric | Before | After | Change |
|---|---|---|---|
| **Total items** | ~100 | ~130 | +30 |
| **Categories** | 23 | 27 (+4 new) | +4 |
| **README lines** | 522 | 616 | +94 |
| **Unrelated items** | 13 | 0 | -13 |
| **Web-specific tools** | ~87 | ~130 | +43 |

---

### 🎯 Impact

**Before:** Mix of web tools + desktop GIS + general visualization + platforms

**After:** Focused exclusively on **web-specific geospatial developer tools**:
- Core mapping libraries
- Browser-based spatial analysis
- Web map UI components (locate, layers, measurement, etc.)
- Web map animation and time-series
- Offline web maps and caching
- Web map printing/export
- Routing/geocoding clients for web
- Tile servers for web clients
- Framework wrappers (React, Vue, Angular, Svelte)
- Web map plugins and extensions

**Result:** More useful for **web developers building geospatial applications**.
