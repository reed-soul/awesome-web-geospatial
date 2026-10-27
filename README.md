# Awesome Web Geospatial

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of web-specific geospatial utilities, tools, and libraries for map-related calculation, visualization, and display.

This list focuses on **web-first** geospatial tools that run in browsers or web environments, covering interactive maps, spatial analysis, 3D visualization, vector tiles, geocoding, routing, and more.

---

## Contents

- [Core Mapping Libraries](#core-mapping-libraries)
- [WebGL/WebGPU Rendering Engines](#webglwebgpu-rendering-engines)
- [3D Globes & Maps](#3d-globes--maps)
- [Spatial Analysis & Geometry](#spatial-analysis--geometry)
- [Vector Tiles & Data Formats](#vector-tiles--data-formats)
- [Spatial Indexing](#spatial-indexing)
- [Geospatial Utilities](#geospatial-utilities)
- [Framework-Specific Components](#framework-specific-components)
- [Geocoding & Routing](#geocoding--routing)
- [Map Drawing & Editing](#map-drawing--editing)
- [Map Controls & UI Components](#map-controls--ui-components)
- [Map Measurement & Editing Tools](#map-measurement--editing-tools)
- [Map Animation & Time Dimension](#map-animation--time-dimension)
- [Map Printing & Export](#map-printing--export)
- [Offline Maps & Caching](#offline-maps--caching)
- [Thematic Mapping & Visualization](#thematic-mapping--visualization)
- [Remote Sensing & Satellite Imagery](#remote-sensing--satellite-imagery)
- [Point Cloud & LiDAR Viewers](#point-cloud--lidar-viewers)
- [Street View & Imagery](#street-view--imagery)
- [Tile Servers & Data Services](#tile-servers--data-services)
- [Map Tile Providers](#map-tile-providers)
- [Web-Based Map Tools](#web-based-map-tools)
- [Plugins & Extensions](#plugins--extensions)
- [Coordinate & Distance Utilities](#coordinate--distance-utilities)
- [Elevation & Terrain Services](#elevation--terrain-services)
- [GeoJSON Validation & Utilities](#geojson-validation--utilities)
- [Cloud-Native Geospatial](#cloud-native-geospatial)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

---

## Core Mapping Libraries

JavaScript libraries for creating interactive web maps.

- **[Leaflet](https://github.com/Leaflet/Leaflet)** - Open-source JavaScript library for mobile-friendly interactive maps. Raster tiles only. Canvas renderer available. Large plugin ecosystem.

- **[MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js)** - Community-led open-source fork of Mapbox GL JS. Vector tiles with WebGL2. BSD-3-Clause license.

- **[OpenLayers](https://github.com/openlayers/openlayers)** - Supports any tile/vector/imagery source. Comprehensive API. Supports OGC standards and experimental GeoZarr.

- **[Mapbox GL JS](https://github.com/mapbox/mapbox-gl-js)** - Vector tiles with WebGL. Proprietary license since v2. Requires Mapbox token.

- **[Maptalks.js](https://github.com/maptalks/maptalks.js)** - 2D/3D maps with plugin architecture.

- **[MapTiler SDK JS](https://github.com/maptiler/maptiler-sdk-js)** - MapLibre-based SDK with additional features. BSD-licensed.

- **[Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript)** - Google's web mapping API with Street View, places, and routing. Proprietary, requires API key and billing.

---

## WebGL/WebGPU Rendering Engines

Frameworks for large-scale geospatial visualization.

- **[deck.gl](https://github.com/visgl/deck.gl)** - Layer-based visualization with GPU acceleration. WebGL2/WebGPU support.

- **[L7 (AntV)](https://github.com/antvis/L7)** - Large-scale geospatial visualization by Ant Group.

- **[CesiumJS](https://github.com/CesiumGS/cesium)** - 3D globe and time-dynamic data.

- **[kepler.gl](https://github.com/keplergl/kepler.gl)** - Full application for geospatial exploration. React-only. Built on deck.gl + MapLibre. Now under Linux Foundation.

- **[Tangram](https://github.com/tangrams/tangram)** - WebGL map rendering for styled 2D/3D maps.

- **[iTowns](https://github.com/iTowns/itowns)** - Three.js-based framework for 3D geospatial visualization. French national geospatial agency (IGN) backed.

- **[GeoJS](https://github.com/OpenGeoscience/geojs)** - Bridges GIS, scientific visualization, and infovis.

---

## 3D Globes & Maps

Libraries for 3D globe and terrain visualization.

- **[globe.gl](https://github.com/vasturiano/globe.gl)** - 3D globe data visualization using ThreeJS/WebGL.

- **[three-globe](https://github.com/vasturiano/three-globe)** - WebGL globe as ThreeJS reusable 3D object.

- **[TerriaJS](https://github.com/TerriaJS/terriajs)** - Library for building 2D/3D geospatial data explorers.

- **[OpenGlobus](https://github.com/openglobus/openglobus)** - Interactive 3D maps with imagery and vector data.

- **[NASA WebWorldWind](https://github.com/NASAWorldWind/WebWorldWind)** - NASA's 3D planetary globe engine. Project maintenance has slowed; services may be intermittent.

---

## Spatial Analysis & Geometry

Client-side geospatial computation and geometry processing.

- **[Turf.js](https://github.com/Turfjs/turf)** - Modular spatial analysis (buffers, intersections, area, etc.). Use individual @turf/* modules instead of full bundle.

- **[JSTS](https://github.com/bjornharrtell/jsts)** - JavaScript Topology Suite. OGC-compliant spatial predicates and functions. Port of Java JTS.

- **[geolib](https://github.com/manuelbieh/geolib)** - Zero-dependency library for basic geospatial operations (distance, bearing, midpoint).

---

## Vector Tiles & Data Formats

Libraries for vector tiles and geospatial data formats.

- **[geojson-vt](https://github.com/mapbox/geojson-vt)** - Converts GeoJSON to vector tiles on the fly. Does not render.

- **[PMTiles](https://github.com/protomaps/PMTiles)** - Single-file archive format for tiled data. Read-only.

- **[FlatGeobuf](https://github.com/flatgeobuf/flatgeobuf)** - Binary encoding based on flatbuffers.

- **[TopoJSON](https://github.com/topojson/topojson)** - GeoJSON extension encoding topology.

- **[geobuf](https://github.com/mapbox/geobuf)** - Compact binary encoding for GeoJSON.

- **[GeoTIFF.js](https://github.com/geotiffjs/geotiff.js)** - Parse GeoTIFF in browser.

- **[geopackage-js](https://github.com/ngageoint/geopackage-js)** - Read GeoPackage files in browser.

- **[shpjs](https://github.com/calvinmetcalf/shapefile-js)** - Parse Shapefiles in browser, returns GeoJSON projected to WGS84.

---

## Spatial Indexing

Data structures and algorithms for spatial queries.

- **[rbush](https://github.com/mourner/rbush)** - Mutable 2D spatial index (R-tree). By Vladimir Agafonkin.

- **[Supercluster](https://github.com/mapbox/supercluster)** - Point clustering library. By Vladimir Agafonkin.

- **[flatbush](https://github.com/mourner/flatbush)** - Static spatial index (packed Hilbert R-tree). By Vladimir Agafonkin.

- **[H3](https://github.com/uber/h3)** - Hexagonal hierarchical spatial index. Use `h3-js` package for browser.

- **[kdbush](https://github.com/mourner/kdbush)** - Static spatial index for 2D points. By Vladimir Agafonkin.

- **[geokdbush](https://github.com/mourner/geokdbush)** - Geographic extension for KDBush. Fast nearest-neighbor queries for locations on Earth. By Vladimir Agafonkin.

- **[tinyqueue](https://github.com/mourner/tinyqueue)** - Tiny priority queue / heap implementation. Used by pathfinding algorithms like Dijkstra/A*. By Vladimir Agafonkin.

---

## Geospatial Utilities

Utilities for common geospatial data formats and operations.

- **[node-geohash](https://github.com/sunng87/node-geohash)** - Geohash encoding/decoding.

- **[geohash-js](https://github.com/davetroy/geohash-js)** - Simple geohash routines.

- **[ngeohash](https://github.com/sunng87/ngeohash)** - Fast geohash for Node.js.

- **[togeojson](https://github.com/mapbox/togeojson)** - Converts KML, GPX to GeoJSON.

- **[osmtogeojson](https://github.com/tyrasd/osmtogeojson)** - Converts OSM data to GeoJSON.

- **[wellknown](https://github.com/mapbox/wellknown)** - Parse and stringify WKT to GeoJSON.

- **[polyline](https://github.com/mapbox/polyline)** - Encode/decode Google Polyline algorithm.

- **[global-mercator](https://github.com/DenisCarriere/global-mercator)** - TMS, XYZ Tiles & Quadkeys utilities.

---

## Framework-Specific Components

Map components for popular frontend frameworks.

### React

- **[react-leaflet](https://github.com/PaulLeCam/react-leaflet)** - React components wrapping Leaflet.

- **[react-map-gl](https://github.com/visgl/react-map-gl)** - React wrapper for MapboxGL / MapLibre.

- **[react-maplibre](https://github.com/visgl/react-maplibre)** - MapLibre-specific React components.

- **[react-simple-maps](https://github.com/zcreativelabs/react-simple-maps)** - Declarative React SVG maps using d3-geo and TopoJSON.

- **[@mapcomponents/react-maplibre](https://github.com/mapcomponents/react-maplibre)** - Declarative React GIS components for MapLibre. Designed for advanced geospatial app development.

### Vue

- **[vue2-leaflet](https://github.com/KoRiGaN/Vue2Leaflet)** - Vue 2 components for Leaflet.

- **[vue-leaflet](https://github.com/vue-leaflet/VueLeaflet)** - Vue 3 components for Leaflet.

- **[vue-mapbox-gl](https://github.com/razorness/vue-mapbox-gl)** - Vue component for Mapbox GL JS.

### Angular

- **[ngx-leaflet](https://github.com/Asymmetrik/ngx-leaflet)** - Angular components for Leaflet.

- **[@maplibre/ngx-maplibre-gl](https://github.com/maplibre/ngx-maplibre-gl)** - Official Angular binding for MapLibre GL JS. Maintained by MapLibre org.

### Svelte

- **[svelte-maplibre](https://github.com/dimfeld/svelte-maplibre)** - Svelte wrapper for MapLibre GL JS.

- **[svelte-leaflet](https://github.com/tanephite/svelte-leaflet)** - Svelte components for Leaflet.

---

## Geocoding & Routing

Libraries and services for address lookup and route calculation.

### Geocoding Clients

- **[leaflet-control-geocoder](https://github.com/perliedman/leaflet-control-geocoder)** - Extendable geocoder control for Leaflet with built-in support for Nominatim, Photon, Pelias, Bing, Mapbox, and more.

- **[MapLibre GL Geocoder](https://github.com/maplibre/maplibre-gl-geocoder)** - Geocoder control for MapLibre GL JS.

### Routing Clients

- **[Leaflet Routing Machine](https://github.com/perliedman/leaflet-routing-machine)** - Multi-backend routing control for Leaflet supporting OSRM, Mapbox Directions, GraphHopper, and Valhalla. Shows route itineraries and alternative routes.

- **[MapLibre GL Directions](https://github.com/maplibre/maplibre-gl-directions)** - Official MapLibre plugin for displaying routing directions on maps.

- **[@graphhopper/directions-api-js-client](https://github.com/graphhopper/graphhopper-directions-api-js-client)** - JavaScript client for GraphHopper Directions API (routing, geocoding, isochrones, matrix).

### Routing/Geocoding Servers (Self-Hosted)

- **[GraphHopper](https://github.com/graphhopper/graphhopper)** - Routing engine. Java library or standalone server.

- **[Nominatim](https://github.com/osm-search/Nominatim)** - OpenStreetMap search engine for geocoding. No official JS SDK.

- **[Photon](https://github.com/komoot/photon)** - Open-source geocoder for OSM data built on Elasticsearch.

- **[OpenRouteService](https://github.com/GIScience/openrouteservice)** - Routing, geocoding, isochrones, matrices.

- **[openrouteservice-js](https://github.com/GIScience/openrouteservice-js)** - JavaScript client for OpenRouteService API.

- **[OSRM](https://github.com/Project-OSRM/osrm-backend)** - Routing engine. C++ backend with Node.js bindings. Self-hosted.

---

## Map Drawing & Editing

Interactive tools for drawing and editing geometries on maps.

- **[Leaflet-Geoman](https://github.com/geoman-io/leaflet-geoman)** - Drawing/editing for Leaflet.

- **[Terra Draw](https://github.com/JamesLMilner/terra-draw)** - Cross-provider drawing (Mapbox, MapLibre, Google Maps, OpenLayers, Leaflet).

- **[Leaflet.draw](https://github.com/Leaflet/Leaflet.draw)** - Legacy drawing plugin for Leaflet.

- **[@mapbox/mapbox-gl-draw](https://github.com/mapbox/mapbox-gl-draw)** - Drawing for Mapbox GL JS.

- **[MapLibre GL Draw](https://github.com/maplibre/maplibre-gl-draw)** - MapLibre-compatible fork of Mapbox GL Draw.

---

## Map Controls & UI Components

Common UI patterns and controls for web maps.

### Location & Navigation

- **[leaflet.locatecontrol](https://github.com/domoritz/leaflet.locatecontrol)** - Geolocation control with watch position, locate bounds, custom markers. Used by osm.org and mapbox.

- **[maplibre-gl-compass](https://github.com/qazsato/maplibre-gl-compass)** - Heading-up compass for MapLibre GL JS. Rotates map based on device orientation.

### Layer Controls

- **[Leaflet.Control.Opacity](https://github.com/dayjournal/Leaflet.Control.Opacity)** - Opacity sliders for tile layers.

- **[Leaflet.StyledLayerControl](https://github.com/davicustodio/leaflet.styledlayercontrol)** - Advanced layer control with grouping, collapsible groups, styled UI.

- **[maplibre-gl-layer-control](https://github.com/opengeos/maplibre-gl-layer-control)** - Layer control with show/hide, opacity control, background layer grouping, legend integration.

- **[map-gl-style-switcher](https://github.com/muimsd/map-gl-style-switcher)** - TypeScript control for switching Mapbox GL / MapLibre GL map styles.

### Map Navigation & View

- **[leaflet-minimap](https://github.com/Norkart/Leaflet-MiniMap)** - Small minimap showing main map's viewport position.

- **[leaflet.fullscreen](https://github.com/brunob/leaflet.fullscreen)** - Fullscreen button using the Fullscreen API.

- **[Leaflet.MousePosition](https://github.com/ardhi/Leaflet.MousePosition)** - Displays coordinates of mouse pointer.

- **[leaflet-hash](https://github.com/mlevans/leaflet-hash)** - Adds dynamic URL hashes to Leaflet maps for bookmarking/sharing.

- **[leaflet-areaselect](https://github.com/heyman/leaflet-areaselect)** - Lets users select bounding box area using resizable overlay.

### Geocoding Controls

- **[MapLibre GL Geocoder](https://github.com/maplibre/maplibre-gl-geocoder)** - Geocoder control for MapLibre GL JS.

- **[leaflet-control-geocoder](https://github.com/perliedman/leaflet-control-geocoder)** - Geocoder control for Leaflet with multiple backend support.

### Legend & Info

- **[leaflet-sidebar](https://github.com/Turbo87/sidebar-v2)** - Collapsible sidebar panel for Leaflet maps.

---

## Map Measurement & Editing Tools

Tools for measuring distance, area, and elevation on web maps.

- **[leaflet-measure](https://github.com/ljagis/leaflet-measure)** - Coordinate, linear, and area measurement tool for Leaflet maps.

- **[Leaflet.Measure](https://github.com/ptma/Leaflet.Measure)** - Distance and area measurement control for Leaflet.

- **[leaflet-measure-path](https://github.com/ProminentEdge/leaflet-measure-path)** - Shows measurements directly on drawn paths/lines/polygons.

- **[@raruto/leaflet-elevation](https://github.com/Raruto/leaflet-elevation)** - Elevation profiles using d3.js. Supports GPX, GeoJSON, KML track import with elevation charts.

---

## Map Animation & Time Dimension

Libraries for animating web maps and handling time-series data.

- **[Leaflet.TimeDimension](https://github.com/socib/Leaflet.TimeDimension)** - Adds time dimension capabilities to Leaflet maps. Manages time layers, time bars, WMS time support. Used for weather/oceanographic data.

- **[maplibre-transition](https://github.com/rowanwins/maplibre-gl-transition)** - Smooth transitions between map styles in MapLibre GL JS.

- **[leaflet-velocity](https://github.com/danwild/leaflet-velocity)** - Visualizes wind fields, ocean currents, and vector data with particle animation effects.

---

## Map Printing & Export

Libraries for exporting web maps as images or video.

- **[leaflet-easyprint](https://github.com/rowanwins/leaflet-easyPrint)** - Print/export icon for Leaflet maps. Supports custom sizing and export modes.

- **[leaflet-image](https://github.com/mapbox/leaflet-image)** - Exports Leaflet maps to images client-side using Canvas and CORS.

- **[leaflet-simple-map-screenshoter](https://github.com/grinat/leaflet-simple-map-screenshoter)** - Promise-based screenshot plugin for Leaflet using dom-to-image.

- **[maplibre-gl-video-export](https://github.com/bjperson/maplibre-gl-video-export)** - Video export plugin for MapLibre GL JS. Exports WebM/MP4 with preset animations.

---

## Offline Maps & Caching

Tools for offline map usage and tile caching.

- **[leaflet.tilelayer.pouchdbcached](https://github.com/maze-map/leaflet.tilelayer.pouchdbcached)** - Leaflet tile layer that caches tiles into PouchDB for offline use.

- **[protomaps-leaflet](https://github.com/protomaps/protomaps-leaflet)** - Enables offline maps with PMTiles format in Leaflet.

- **[leaflet-pmtiles-layer](https://github.com/eliotjordan/leaflet-pmtiles-layer)** - Leaflet plugin for PMTiles formatted vector data.

---

## Thematic Mapping & Visualization

Libraries for creating thematic maps and visualizations.

- **[heatmap.js](https://github.com/pa7/heatmap.js)** - HTML5 canvas-based heatmap. Unmaintained.

- **[Bertin.js](https://github.com/neocarto/bertin)** - Thematic SVG maps for geospatial data.

- **[d3-geo](https://github.com/d3/d3-geo)** - D3 geographic projections and path generators.

- **[d3-geo-projection](https://github.com/d3/d3-geo-projection)** - Extended geographic projections for d3-geo.

---

## Remote Sensing & Satellite Imagery

Libraries for satellite imagery and remote sensing data in the browser.

- **[geoblaze](https://github.com/GeoTIFF/geoblaze)** - JavaScript raster processing engine.

---

## Point Cloud & LiDAR Viewers

Web-based viewers for large point cloud datasets.

- **[Potree](https://github.com/potree/potree)** - WebGL point cloud viewer for LiDAR data.

- **[Plasio](https://github.com/verma/plasio)** - Drag-and-drop in-browser LAS/LAZ point cloud viewer.

---

## Street View & Imagery

Libraries for street-level imagery in web maps.

- **[MapillaryJS](https://github.com/mapillary/mapillary-js)** - JavaScript library for street imagery experiences.

- **[maplibre-gl-streetview](https://github.com/opengeos/maplibre-gl-streetview)** - Street View control for MapLibre GL JS with Google Street View and Mapillary support.

---

## Tile Servers & Data Services

Backend services for serving map tiles to web clients.

- **[GeoServer](https://github.com/geoserver/geoserver)** - Java server for geospatial data with OGC standards.

- **[Koop](https://github.com/koopjs/koop)** - JavaScript toolkit for translating, querying geospatial APIs.

- **[TiTiler](https://github.com/developmentseed/titiler)** - Cloud-optimized GeoTIFF (COG) tile server.

- **[TileStrata](https://github.com/naturalatlas/tilestrata)** - Pluggable Node.js map tile server.

- **[Martin](https://github.com/urbica/martin)** - Fast tile server for PostGIS, MBTiles, PMTiles. Rust-based.

- **[TileServer GL](https://github.com/maptiler/tileserver-gl)** - Vector and raster tiles from one server.

---

## Map Tile Providers

Tile services for web maps.

- **[OpenStreetMap](https://www.openstreetmap.org/)** - Free world map tiles from OSM community.

- **[leaflet-providers](https://github.com/leaflet-extras/leaflet-providers)** - Configurations for various free tile providers.

- **[CARTO](https://carto.com/)** - Cloud-based platform for spatial analysis.

- **[Stadia Maps](https://stadiamaps.com/)** - Commercial map tiles with free tier. Includes former Stamen Design styles.

- **[Mapbox](https://www.mapbox.com/)** - Platform for custom maps with free tier.

- **[MapTiler](https://www.maptiler.com/)** - Vector and raster tiles.

- **[Thunderforest](https://www.thunderforest.com/)** - Map tiles with specialized styles.

---

## Web-Based Map Tools

Ready-to-use web applications for geospatial data.

- **[GIS Toolbox](https://gis.taoliapp.com/)** - Free browser GIS tools for coordinate conversion (WGS84/UTM/EPSG/GCJ-02/BD-09), Shapefile/GeoJSON/KML, and map measurement; files stay on-device.
- **[mapshaper](https://github.com/mbloch/mapshaper)** - Online editor for Shapefile/GeoJSON/TopoJSON/CSV with simplification.

- **[geojson.io](https://github.com/mapbox/geojson.io)** - Web tool for creating and sharing spatial data.

- **[overpass-turbo](https://github.com/tyrasd/overpass-turbo)** - Data mining tool for OpenStreetMap.

- **[Maputnik](https://github.com/maputnik/editor)** - Visual editor for Mapbox GL styles.

---

## Plugins & Extensions

Popular plugins for core mapping libraries.

### Leaflet Plugins

- **[Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)** - Marker clustering for Leaflet.

- **[Leaflet.heat](https://github.com/Leaflet/Leaflet.heat)** - Heatmap plugin for Leaflet.

- **[esri-leaflet](https://github.com/Esri/esri-leaflet)** - Leaflet plugins for ArcGIS services.

- **[Leaflet.VectorGrid](https://github.com/Leaflet/Leaflet.VectorGrid)** - Display vector data in Leaflet.

- **[leaflet.wms](https://github.com/heigeo/leaflet.wms)** - Full-featured WMS plugin for Leaflet supporting single-tile, tiled, and non-tiled layers with GetFeatureInfo.

- **[mapbox-gl-leaflet](https://github.com/mapbox/mapbox-gl-leaflet)** - MapLibre/Mapbox GL integration with Leaflet API.

- **[maplibre-gl-leaflet](https://github.com/maplibre/maplibre-gl-leaflet)** - Bridge allowing MapLibre GL JS layers inside Leaflet maps.

### OpenLayers Extensions

- **[ol-ext](https://github.com/Viglino/ol-ext)** - Extensions for OpenLayers (200+ controls).

- **[ol-mapbox-style](https://github.com/boundlessgeo/ol-mapbox-style)** - Use Mapbox Style with OpenLayers.

### MapLibre Plugins

- **[MapLibre GL Geocoder](https://github.com/maplibre/maplibre-gl-geocoder)** - Geocoder control for MapLibre GL JS.

- **[MapLibre GL Compare](https://github.com/maplibre/maplibre-gl-compare)** - Synchronized map comparison.

- **[maplibre-gl-inspect](https://github.com/maplibre/maplibre-gl-inspect)** - Plugin for inspecting vector data, showing feature IDs and properties.

- **[maplibre-gl-layer-control](https://github.com/opengeos/maplibre-gl-layer-control)** - Comprehensive layer control with opacity, show/hide, legend integration.

- **[map-gl-style-switcher](https://github.com/muimsd/map-gl-style-switcher)** - Control for switching map styles.

- **[maplibregl-mapbox-request-transformer](https://github.com/rowanwins/maplibregl-mapbox-request-transformer)** - Transform Mapbox URLs for MapLibre.

### 3D Integration

- **[Threebox](https://github.com/jscastro76/threebox)** - Abstracts Three.js for adding 3D models to Mapbox/MapLibre maps via CustomLayerInterface.

---

## Coordinate & Distance Utilities

Libraries for coordinate transformations and distance calculations.

- **[Proj4js](https://github.com/proj4js/proj4js)** - Transform coordinates between coordinate systems.

- **[geodesy](https://github.com/ChrisVeness/geodesy)** - Geodesy functions (distance, bearing, destination).

- **[geographiclib-js](https://github.com/geographiclib/geographiclib-js)** - JavaScript implementation of geodesic routines.

- **[arc.js](https://github.com/springmeyer/arc.js)** - Calculate great circle routes as GeoJSON or WKT.

- **[coordtransform](https://github.com/wandergis/coordtransform)** - Chinese coordinate systems (GCJ-02, BD-09, WGS-84).

- **[projections-js](https://github.com/ngageoint/projections-js)** - NGA library for projection conversions.

---

## Elevation & Terrain Services

APIs and services for terrain and elevation data.

- **[Open Topo Data](https://github.com/ear7h/opentopodata)** - REST API server for elevation data.

- **[Open-Meteo Elevation API](https://open-meteo.com/en/docs/elevation-api)** - Free elevation API with 90m resolution.

- **[Google Elevation API](https://developers.google.com/maps/documentation/elevation)** - Google's elevation service.

- **[Tangram Heightmapper](https://tangrams.github.io/heightmapper)** - WebGL elevation data browser.

- **[Valhalla Elevation](https://github.com/valhalla/valhalla)** - Open-source routing with elevation lookup.

---

## GeoJSON Validation & Utilities

Libraries for GeoJSON validation and processing.

- **[@placemarkio/check-geojson](https://github.com/placemark/check-geojson)** - Modern GeoJSON validator.

- **[geojsonhint](https://github.com/mapbox/geojsonhint)** - Standards-based GeoJSON validation. Archived.

- **[@turf/clean-coords](https://github.com/Turfjs/turf)** - Remove redundant coordinates.

- **[@turf/flip](https://github.com/Turfjs/turf)** - Flip coordinate order.

- **[@turf/simplify](https://github.com/Turfjs/turf)** - Simplify geometry.

- **[@turf/bbox](https://github.com/Turfjs/turf)** - Calculate bounding box.

---

## Cloud-Native Geospatial

Cloud-optimized formats and libraries for geospatial data.

- **[GeoParquet](https://github.com/opengeospatial/geoparquet)** - Geospatial data in Apache Parquet format.

- **[loaders.gl](https://github.com/visgl/loaders.gl)** - Framework-independent loaders for geospatial and 3D data.

- **[gdal3.js](https://github.com/bugra9/gdal3.js)** - Convert raster/vector data in browser via WebAssembly.

- **[COG (Cloud Optimized GeoTIFF)](https://www.cogeo.org/)** - GeoTIFF optimized for cloud access.

- **[STAC (SpatioTemporal Asset Catalog)](https://stacspec.org/)** - Standardized metadata for geospatial assets.

---

## Style Specification & Validation

Tools for working with map style specifications.

- **[@maplibre/maplibre-gl-style-spec](https://github.com/maplibre/maplibre-gl-style-spec)** - Code and utilities for the MapLibre Style Specification. Used for programmatic style generation and validation.

---

## Learning Resources

Tutorials, courses, and documentation.

### Documentation & Guides

- [MapLibre GL JS Docs](https://maplibre.org/maplibre-gl-js/docs/)
- [OpenLayers Examples](https://openlayers.org/en/latest/examples/)
- [Leaflet Tutorials](https://leafletjs.com/examples.html)
- [deck.gl Documentation](https://deck.gl/docs)
- [Made with MapLibre](https://madewithmaplibre.com/) - Showcase of MapLibre projects and tutorials

### Communities

- [r/gis](https://www.reddit.com/r/gis/) - GIS community on Reddit.
- [GIS Stack Exchange](https://gis.stackexchange.com/) - Q&A for GIS professionals.
- [OpenStreetMap Community](https://community.openstreetmap.org/) - OSM forums.
- [MapLibre Discord](https://discord.com/invite/Xy3YKCHxdF) - MapLibre community chat.

---

## Related Awesome Lists

- [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial) - Comprehensive geospatial tools
- [Awesome Frontend GIS](https://github.com/joewdavies/awesome-frontend-gis) - Frontend GIS resources
- [Awesome GeoJSON](https://github.com/tmcw/awesome-geojson) - GeoJSON tools
- [Awesome OpenStreetMap](https://github.com/osmlab/awesome-openstreetmap) - OSM ecosystem
- [Awesome PostGIS](https://github.com/postgis/awesome-postgis) - PostGIS tools
- [Awesome Spatial DB](https://github.com/daattali/awesome-spatial-db) - Spatial databases
- [Awesome Mapping](https://github.com/zzmp/awesome-mapping) - Mapping tools

---

## Contributing

Contributions welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

Guidelines:
- Focus on web-specific geospatial tools
- Describe what the tool does and its characteristics
- Include known limitations
- Use objective language

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, contributors have waived all copyright and related rights to this work.
