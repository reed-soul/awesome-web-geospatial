# Contributing to Awesome Web Geospatial

Your contributions are welcome!

## Contribution Guidelines

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Focus on **web-specific** geospatial tools and libraries.
- Describe what the tool does and its characteristics.
- Include known limitations and trade-offs.

## Entry Format

Use the following format for entries:

```markdown
- **[Tool Name](https://link)** - Description of what it does and its characteristics. Include known limitations.
```

For longer descriptions, write a concise paragraph (2-4 sentences) covering:
- What the tool/library does
- Key technical characteristics (rendering approach, dependencies, etc.)
- Known limitations or considerations
- Ecosystem/community context if relevant

## What We Include

✅ **Web-first geospatial tools:**
- JavaScript/TypeScript libraries for web mapping
- Browser-based geospatial computation
- Web map plugins and extensions
- Web map UI components (controls, popups, etc.)
- Client-side geospatial data format readers
- Web APIs for geospatial services
- Tools for offline web maps, printing, animation
- Backend tile servers specifically for web map serving

✅ **Description should cover:**
- What the tool does
- Technical characteristics (WebGL, raster vs vector, dependencies)
- Known limitations or constraints
- License type if relevant (open-source vs proprietary)
- Browser/runtime requirements
- Ecosystem context (e.g., "fork of X", "part of Y ecosystem")

## What We Don't Include

❌ **Not web-specific:**
- Desktop GIS applications (QGIS, ArcGIS Desktop)
- Command-line tools without web interfaces
- Python/R geospatial libraries (unless they have web/browser usage)
- Database systems (PostgreSQL/PostGIS - belongs in awesome-postgis)

❌ **General-purpose tools:**
- Tools not specific to geospatial (e.g., general charting libraries)
- Abstract geometry/math libraries without earth/CRS awareness
- General 3D visualization (unless geospatial-specific)

❌ **Platforms and services (not developer tools):**
- SaaS platforms without SDKs/APIs
- Data collection platforms
- End-user web applications (not libraries/tools)
- Proprietary cloud computation platforms

❌ **Unmaintained/defunct tools:**
- Tools with no activity for 3+ years
- Projects with broken links or deprecated status
- Superseded by clearly better alternatives (unless historically significant)

## What to Avoid in Descriptions

- ❌ Bundle sizes (they change, depend on build configuration)
- ❌ Download counts (they fluctuate, don't indicate quality)
- ❌ Performance benchmarks (context-dependent)
- ❌ Star counts (don't indicate usefulness)
- ❌ Subjective language ("best", "amazing", "powerful", "blazing fast")
- ❌ Recommendations (users decide based on their needs)

## Categories

Place entries in the most appropriate category:

- **Core Mapping Libraries** - Main JavaScript mapping libraries
- **WebGL/WebGPU Rendering Engines** - High-performance visualization
- **3D Globes & Maps** - 3D globe and terrain visualization
- **Spatial Analysis & Geometry** - Client-side geospatial computation
- **Vector Tiles & Data Formats** - Vector tiles and geospatial data formats
- **Spatial Indexing** - Fast spatial query data structures
- **Geospatial Utilities** - Format converters, geohash, KML/GPX tools
- **Framework-Specific Components** - React, Vue, Angular, Svelte wrappers
- **Geocoding & Routing** - Address lookup and route calculation
- **Map Drawing & Editing** - Interactive geometry editing
- **Map Controls & UI Components** - Common UI patterns (locate, layers, fullscreen, etc.)
- **Map Measurement & Editing Tools** - Distance, area, elevation measurement
- **Map Animation & Time Dimension** - Temporal data and animations
- **Map Printing & Export** - Screenshot, image, video export
- **Offline Maps & Caching** - PWA, tile caching, offline support
- **Thematic Mapping & Visualization** - Specialized visualizations
- **Remote Sensing & Satellite Imagery** - Satellite imagery tools
- **Point Cloud & LiDAR Viewers** - Point cloud visualization
- **Street View & Imagery** - Street-level imagery
- **Tile Servers & Data Services** - Backend tile serving
- **Map Tile Providers** - Commercial/free tile services
- **Web-Based Map Tools** - Ready-to-use web applications
- **Plugins & Extensions** - Plugins for core libraries
- **Coordinate & Distance Utilities** - Coordinate transformations
- **Elevation & Terrain Services** - Elevation APIs
- **GeoJSON Validation & Utilities** - GeoJSON validators
- **Cloud-Native Geospatial** - Cloud-optimized formats
- **Style Specification & Validation** - Map style tools
- **Learning Resources** - Tutorials, docs, communities

## Adding New Categories

If you need to add a new category:

1. Add it to the Contents section
2. Create the section with a brief description
3. Ensure the category fits the web-specific scope
4. Add at least 2-3 entries

## Questions?

Open an issue if you have questions about categorization or inclusion.

---

Thanks for contributing!
