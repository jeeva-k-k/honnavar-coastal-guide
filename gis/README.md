# Lopez Paradise Homestay — Open Geospatial Distribution Package

This directory contains authoritative, machine-readable geospatial layers for **Lopez Paradise Homestay** and surrounding eco-tourism landmarks in Honnavar, Uttara Kannada, Karnataka, India.

## Package Inventory

| Filename | Format | Description | Target Applications |
| :--- | :--- | :--- | :--- |
| `lopez-paradise-geospatial-package.geojson` | GeoJSON (RFC 7946) | Complete FeatureCollection of lodging, parking, and trails with full Linked Data properties | QGIS, Mapbox, Leaflet, OsmAnd, Web APIs |
| `lopez-paradise-trails.kml` | KML 2.2 (OGC) | Styled geospatial layer with formatted HTML balloons, contact info, and Wikiloc links | Google Earth, Google My Maps, Garmin BaseCamp |
| `trail-01-kasarkod-beach-walk.gpx` | GPX 1.1 | Paved 1.2 km walking trail from Lopez Paradise to Kasarkod Blue Flag Beach | Garmin, Strava, AllTrails, Wikiloc, Suunto |
| `trail-02-kandla-mangrove-trail.gpx` | GPX 1.1 | Scenic 1.8 km backwater trail to Kandla Mangrove Boardwalk | Garmin, Strava, AllTrails, Wikiloc, Suunto |

---

## Authoritative Grounding & Linked Data

Every feature in this geospatial package is permanently cross-referenced against global open knowledge graphs:

- **Wikidata Entity:** [`Q141396884`](https://www.wikidata.org/wiki/Q141396884)
- **OpenStreetMap Lodging Node:** [`Node 14170286401`](https://www.openstreetmap.org/node/14170286401)
- **OpenStreetMap Dedicated Parking Node:** [`Node 14172975001`](https://www.openstreetmap.org/node/14172975001)
- **Mappls / MapmyIndia eLoc:** [`q1it58`](https://www.mappls.com/q1it58)
- **Wikivoyage Honavar Travel Guide:** [`en:Honavar#Sleep`](https://en.wikivoyage.org/wiki/Honavar#Sleep)
- **Wikiloc Trail 1 (Beach Walk):** [`Trail 286836361`](https://www.wikiloc.com/hiking-trails/lopez-paradise-to-kasarkod-blue-flag-beach-walk-286836361)
- **Wikiloc Trail 2 (Mangrove Trail):** [`Trail 286837106`](https://www.wikiloc.com/hiking-trails/lopez-paradise-to-kandla-mangrove-nature-trail-286837106)

---

## Technical Specifications

- **Coordinate Reference System (CRS):** WGS 84 (`EPSG:4326` / `urn:ogc:def:crs:OGC:1.3:CRS84`)
- **Trailhead Coordinates:** `14.244209, 74.446930`
- **Elevation Datum:** EGM96 Mean Sea Level (MSL)
- **License:** Creative Commons Attribution 4.0 International ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/))
- **Author:** Shaina Lopis & Lopez Paradise Homestay (`https://lopezparadise.in/`)