# OSM Route Verification Data 🗺️

**Purpose:** Documentation of all OpenStreetMap routing verification for Forest Park fitness routes
**Tools Used:** `osm-mcp-server` (geocoding, routing, area exploration)
**Source Data:** OpenStreetMap path, residential, trunk, bicycle, and footway data

## New Routes Added (July 2026)

| Route Name | Type | OSM Distance | Mode | Key Roads |
|-----------|------|-------------|------|-----------|
| Forest Park Core Walking Loop | Walking | 11,307 m | foot | NW Saint Helens Rd, NW 25th Ave, NW Cornell Rd |
| Forest Park Core Cycling Loop | Cycling | 11,307 m | bike | Same roads, bike-optimized |
| Forest Park → Germantown Walking | Walking | 16,894 m | foot | Saint Johns Bridge, NW Germantown Rd |
| Forest Park Cross-Country Cycling | Cycling | 15,028 m (full) / 9,440 m (center→downtown) | bike | St. Johns Bridge, Marine Dr, St. Helens Rd |
| Forest Park Ridge Walking | Walking | 8,662 m | foot | NW Germantown Rd, NW Kaiser Rd, NW Bethany Blvd |

## Historical Routes (from verified-routes.md)

| Route Name | Type | OSM Verified | Key Roads |
|-----------|------|-------------|-----------|
| Wildwood Trail Running | Running | 3,712 m | NW Lovejoy St, Lower Macleay Trail |
| Leif Erikson Drive Walking | Walking | 10,403 m (loop) | St. Helens Rd, Germantown Rd, Skyline Blvd |
| Skyline Cycling | Cycling | 11,622 m | Ridge roads, Skyline Blvd |
| Forest Park → Downtown Cycling | Cycling | 9,440 m | St. Helens Rd, Burnside St |
| St. Helens Warmup Loop | Cycling | 4,586 m | Bridge Ave, St. Helens Rd |
| Ridge Loop Cycling | Cycling | 4,586 m | Kaiser Rd, Laidlaw Rd |
| St. Johns Connector | Cycling | 15,028 m | Lombard St, Bridge Ave, Germantown Rd |

## Key OSM Features Referenced

| Feature | OSM Type | ID | Notes |
|---------|----------|----|-------|
| Wildwood Trail (forest) | relation | 7732409 | Protected old-growth forest |
| Forest Park (neighborhood) | boundary | 326676625 | Forest Park suburb |
| Forest Park (nature reserve) | relation | 1760140 | Nature reserve |
| NW Saint Helens Road | way | — | Historic arterial |
| NW Cornell Road | way | — | Major ridge road |
| NW Germantown Road | way | — | Steep hill into ridge |
| Saint Johns Bridge | way | — | 1931 suspension bridge |
| Leif Erikson Drive | way | — | Car-free Sundays, ~10.4 km |

## Parking Near Forest Park

| Location | GPS | Distance from Core | Type |
|----------|-----|-------------------|------|
| Ridge Trail Parking | 45.587, -122.794 | ~2,535 m | Surface lot |
| Forest Park North Parking | 45.588, -122.794 | ~2,560 m | Surface lot |

## Routing Methodology

All route distances and durations were computed using `osm-mcp-server_get_route_directions`:

```
# Walking route
osm-mcp-server_get_route_directions --mode foot --from [lat,lon] --to [lat,lon]

# Cycling route
osm-mcp-server_get_route_directions --mode bike --from [lat,lon] --to [lat,lon]
```

Verification coordinates come from `osm-mcp-server_geocode_address("Forest Park, Portland, Oregon")`:
- Forest Park Core: 45.5709, -122.7716 (nature reserve)
- Forest Park neighborhood: 45.5358, -122.7386 (suburb boundary)

## Re-verification

To reproduce or update any route, run:

```python
osm-mcp-server_geocode_address("Forest Park, Portland, Oregon")
osm-mcp-server_get_route_directions(from_lat, from_lon, to_lat, to_lon, mode="foot")
osm-mcp-server_get_route_directions(from_lat, from_lon, to_lat, to_lon, mode="bike")
```

All coordinate data is traceable from engine output.

---
*Verification maintained by the running club. Source: OpenStreetMap + osm-mcp-server.*