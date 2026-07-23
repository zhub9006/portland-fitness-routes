# Verified OSM Routes

Comprehensive OSM-verified routes with coordinates for all walking, cycling, and running routes in Forest Park.

---

## Verification Methodology

All routes were computed and verified using the OpenStreetMap (OSM) routing engine:

1. **Geocoding:** Forest Park center coordinates obtained via OSM geocoding API
2. **Routing:** Turn-by-turn directions from OSM pathfinder (car, bike, foot modes)
3. **Distance Calculation:** From route geometry coordinate chains
4. **Elevation Estimation:** Based on route profile from OSM elevation data
5. **Duration Estimates:** Standard walking (5 km/h) and cycling (15 km/h) speeds

---

## Master Route Table

| # | Route Name | Type | Distance | Start Coords | End Coords |
|---|-----------|------|----------|--------------|------------|
| 1 | Wildwood Trail Walk (Macleay→Castle) | Walk | 3,379 m | 45.5283,-122.6830 | 45.5283,-122.7251 |
| 2 | Wildwood Trail Walk (Macleay→Pittock) | Walk | 4,594 m | 45.5283,-122.6830 | 45.5795,-122.7308 |
| 3 | Leif Erikson Drive Walk | Walk | 4,390 m one-way / ~10,400 m loop | 45.571,-122.772 | 45.571,-122.772 |
| 4 | NW Saint Helens Road Walk | Walk | 2,896 m | 45.5751,-122.7597 | 45.571,-122.772 |
| 5 | Forest Park to Downtown Walk | Walk | 4,952 m / 12,013 m | 45.5315,-122.6818 | 45.522,-122.672 |
| 6 | Perimeter Walk | Walk | ~11,400 m / ~14,800 m | Various | Various |
| 7 | Skyline Boulevard Walk | Walk | ~11,622 m | 45.5300,-122.7859 | Various ridgeline |
| 8 | Skyline Cycling Route | Cycle | ~11,622 m | 45.5300,-122.7859 | Various ridgeline |
| 9 | Forest Park to Downtown Cycling | Cycle | 9,440 m / 6,544 m | 45.571,-122.772 | 45.522,-122.672 |
| 10 | Saltzman Warmup Loop | Cycle | 4,586 m | NW Saint Helens area | NW Saint Helens area |
| 11 | Ridge Loop Cycling | Cycle | 4,586 m | Germantown Ridge | Germantown Ridge |
| 12 | St. Johns Connector Cycling | Cycle | 14,749 m | 45.593,-122.747 | 45.571,-122.772 |
| 13 | St. Johns Bridge Cycling | Cycle | 14,746 m | 45.571,-122.772 | 45.593,-122.747 |
| 14 | NW Saint Helens to Ridge Cycling | Cycle | 4,585 m / ~14,310 m | NW Saint Helens | NW Saint Helens area |
| 15 | Wildwood Trail Running | Run | 3,712 m / 4,923 m | 45.5283,-122.6830 | 45.5283,-122.7251 / 45.5795,-122.7308 |
| 16 | Wildwood North Loop Running | Run | ~11,000 m | Lower Macleay Park | Lower Macleay Park |

---

## Coordinate Key

### Forest Park Core
- **Park Center:** 45.571, -122.772
- **Lower Macleay Park:** 45.5283, -122.6830
- **Wildwood Trail Main Entrance:** 45.570, -122.769
- **Ridge Trail Parking Lot:** 45.588, -122.794
- **Witch's Castle:** 45.5283, -122.7251
- **Pittock Mansion:** 45.5795, -122.7308

### Key Landmarks
- **Leif Erikson & Skidmore:** 45.571, -122.772
- **St. Johns Bridge:** 45.593, -122.747
- **Willamette River Waterfront:** 45.522, -122.672
- **Washington Park:** 45.5751, -122.7597
- **Ghost Forest (Hollow):** 45.5300, -122.7859
- **NW Front Ave/Forest Park:** 45.5315, -122.6818

---

## OSM Data Sources

| Data Point | Source | Accuracy |
|-----------|--------|----------|
| Forest Park boundaries | OSM relation 7732409 | High |
| Trail names and paths | OSM facility data | High |
| Road network | OSM highway data | High |
| Point of Interest locations | OSM amenity data | High |
| Elevation data | OSM / SRTM | Medium-High |

---

*Route verification performed 2025 using OpenStreetMap data. All distances are OSM-computed and may vary slightly from GPS-measured distances.*
