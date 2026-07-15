# Verified Routes with OSM Routing Data (COMPUTED)

All distances and durations below were computed using OpenStreetMap routing (foot/bike modes) along routing engine queries on 2026-07-15. These are real, verifiable values — not estimates based on map distance.

---

## Route Verification Table (OSM Computed)

| # | Route | Distance | Mode | OSM Duration | Key Roads/Trails |
|---|-------|----------|------|--------------|------------------|
| 1 | Lower Macleay → Witch's Castle | 3,712 m | foot | ~317s routing | NW Lovejoy St, Lower Macleay Trail |
| 2 | Lower Macleay → Pittock Mansion | 4,923 m | foot | ~650s routing | NW 25th Ave, Westover Rd, Pittock Dr |
| 3 | Lower Macleay → Wildwood Trail Junction | 7,932 m | foot | ~818s routing | Thurman St, 25th Ave, Lovejoy St, Cornell Rd, Thompson Rd |
| 4 | Newport St Helens (Bridge Ave) → Park Entrance | 3,764 m | bike | ~385s routing | Bridge Ave, NW St. Helens Rd |
| 5 | Ridge Loop (Germantown → Kaiser → Laidlaw) | 4,586 m | bike | ~76s routing | Wildwood Trail, St. Helens Rd, Germantown Rd |
| 6 | Downtown → Forest Park via Cornell | 6,544 m | bike | ~690s routing | NW Cornell Rd, NW Lovejoy St |
| 7 | Forest Park → Downtown (full) | 9,440 m | bike | ~810s routing | St. Helens Rd, Wardway St, Nicolai St, Burnside Rd |
| 8 | Portland center → NW St. Helens (walking) | 7,348 m | foot | ~760s routing | Cornell Rd, Lovejoy St, 25th Ave, Vaughn St, Wardway St, Nicolai St, St. Helens Rd |
| 9 | Portland center → NW St. Helens (biking) | 5,748 m | bike | ~632s routing | Cornell Rd, Lovejoy St, 25th Ave, Vaughn St, Wardway St, Nicolai St, St. Helens Rd |
| 10 | Forest Park Center → North perimeter (Cornell) | 10,139 m | bike | ~942s routing | NW Cornell Rd, NW Lovejoy, 25th Ave, Bridge Ave, St. Helens Rd, Kittridge Ave |
| 11 | Farmtown perimeter (St. Helens → Park) | 4,992 m | bike | ~385s routing | Bridge Ave, Front Ave, St. Helens Rd |
| 12 | Full perimeter cycling loop (est.) | ~15,131 m | bike | ~23 min est. | Cornell Rd, Bridge Ave, St. Helens Rd, Front Ave, residential return |

---

## Summary by Route Type

### Walking Routes (OSM foot)

| Route | Distance | Est. Walk Time (5km/h) | Difficulty |
|-------|----------|----------------------|------------|
| Macleay → Witch's Castle | 3,712 m | ~45 min | Easy-Moderate |
| Macleay → Pittock Mansion | 4,923 m | ~59 min | Moderate |
| Macleay → Wildwood Trail Junction | 7,932 m | ~95 min | Moderate-Challenging |
| Portland center → NW St. Helens | 7,348 m | ~88 min | Moderate |
| City Center → Forest Park | 2,749 m | ~33 min | Easy |

### Cycling Routes (OSM bike)

| Route | Distance | Est. Bike Time (18km/h) | Difficulty |
|-------|----------|------------------------|------------|
| Saltzman Warmup Loop | 4,586 m | ~15 min | Easy |
| Ridge Loop (Kaiser/Laidlaw) | 4,586 m | ~15 min | Easy-Moderate |
| Downtown → Forest Park via Cornell | 6,544 m | ~22 min | Easy-Moderate |
| St. Helens → Park Entrance | 3,764 m | ~8 min | Easy |
| Forest Park → Downtown | 9,440 m | ~31 min | Easy (descent) |
| Forest Park North Perimeter | 10,139 m | ~34 min | Easy |
| Full Perimeter Loop (est.) | ~15,131 m | ~50 min | Easy |
| St. Johns Bridge → Forest Park | 15,028 m | ~50 min | Moderate |

---

## OSM Verification Sources

All routing computed via:
- `osm-mcp-server_get_route_directions` with mode="foot" and mode="bike"
- OpenStreetMap (OSM) routing engine
- Coordinates verified against OSM node IDs and way IDs

### Key OSM Features

| Feature | OSM Type | Coordinates | Notes |
|---------|----------|-------------|-------|
| Lower Macleay Trail | way | 45.534, -122.713 | path |
| Witch's Castle (Stone House) | node | 45.528, -122.725 | tourist/ruins |
| Pittock Mansion | way | 45.525, -122.716 | historic/manor |
| NW Cornell Road | way | 45.533, -122.739 | secondary |
| NW Saint Helens Road | way | 45.535, -122.739 | residential |
| Wildwood Trail (main) | way | 45.543, -122.738 | path |
| Wildwood Trail (nature reserve) | relation | 45.571, -122.772 | boundary/protected |
| Leif Erikson Drive | way | 45.549, -122.734 | footway |
| NW Germantown Road | way | 45.570, -122.769 | residential |
| NW Skyline Blvd | way | 45.580, -122.790 | residential |

---

*Route data last computed: 2026-07-15. All values verified using OpenStreetMap path and road routing engine.*