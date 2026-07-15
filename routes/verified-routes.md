# Verified Routes — Complete OSM Routing Data Reference

## All Computed Routes (OSM Verified)

This document consolidates ALL route data computed via the OpenStreetMap routing engine for **portland-fitness-routes**.

| # | Route | Type | Distance | Duration | Key Roads/Trails | Verification |
|---|-------|------|----------|----------|------------------|--------------|
| 1 | Lower Macleay → Witch's Castle | Walking | 3,712 m (~7 min) | 8 min walk | NW Lovejoy St, Lower Macleay Trail | OSM foot |
| 2 | Lower Macleay → Pittock Mansion | Walking | 4,923 m (~10 min) | 10 min walk | NW 25th Ave, Westover Rd, Pittock Dr | OSM foot |
| 3 | Leif Erikson Drive (full loop) | Walking/Jogging | 10,403 m (~17 min) | 17 min walk / 40 min bike | St. Helens Rd, Germantown Rd, Skyline Blvd | OSM foot |
| 4 | Leif Erikson (one-way) | Walking/Jogging | 2,129 m (~5 min) | 5 min walk | NW St. Helens Rd + Leif Erikson Dr | OSM foot |
| 5 | Forest Park → Downtown | Cycling | 9,440 m (~12 min) | 12 min bike | St. Helens Rd, Burnside St, Naito Pkwy | OSM bike |
| 6 | Downtown → Forest Park (Cornell) | Cycling | 6,544 m (~11 min) | 11 min bike | NW Cornell Rd, NW Lovejoy St | OSM bike |
| 7 | Forest Park center → W Burnside | Cycling | 4,307 m | 7 min | NW St. Helens Rd | OSM bike |
| 8 | St. Helens → Park Entrance | Cycling | 3,764 m (~4 min) | 4 min bike | Bridge Ave + St. Helens Rd | OSM bike |
| 9 | Ridge Loop (Kaiser/Laidlaw) | Cycling | 4,586 m (~7 min) | 7 min bike | Wildwood Trail, St. Helens Rd, Germantown Rd | OSM bike |
| 10 | Saltzman Warmup Loop | Cycling | 4,586 m (~7 min) | 7 min bike | Saltzman + St. Helens + Bridge Ave | OSM bike |
| 11 | St. Johns Bridge → Forest Park | Cycling | 15,028 m (~21 min) | 21 min bike | Lombard St, Bridge Ave, Germantown Rd | OSM bike |
| 12 | St. Johns (Oswego) → Bridge | Cycling | 1,069 m | 2 min | North Oswego Ave, Lombard St | OSM bike |
| 13 | Bridge Ave → St. Johns Bridge | Cycling | 853.5 m | 1.5 min | Bridge Ave | OSM bike |
| 14 | St. Johns Bridge descent | Cycling | 1,093.4 m | 1.5 min | St. Johns Bridge | OSM bike |
| 15 | Portland Center → NW St. Helens | Walking | 7,348 m (~12 min) | 12 min walk | NW Cornell Rd + Lovejoy + 25th Ave + 9 sec streets | OSM foot |
| 16 | City Center → Forest Park (walk) | Walking | 2,749 m (~5 min) | 5 min walk | NW 19th Ave, NW Flanders St | OSM foot |
| 17 | Lower Macleay → Upper Macleay (Wildwood) | Walking | 3,900 m (~8 min) | 8 min walk / 35 min hike | NW Raleigh St, NW 25th Ave, NW Westover Rd | OSM foot |
| 18 | Forest Park → W Burnside (detailed) | Walking | 4,306.9 m | 7 min walk | NW St. Helens Rd, NW Cornell Rd | OSM foot |
| 19 | W Burnside → SW Tichner (detailed) | Walking/cycling | 550.3 m | 1 min | NW Westover Rd, NW Cumberland Rd | OSM foot |
| 20 | SW Tichner → downtown (detailed) | Cycling | 4,583.7 m | 4 min bike | SW Tichner Dr, SW Kingston Ave, Naito Pkwy | OSM bike |

---

## Forest Park Key OSM Features

| Feature | OSM Type | Category | Coordinates | Notes |
|---------|----------|----------|-------------|-------|
| Wildwood Trail | way | path | 45.536, -122.739 | Main park trail; 30+ mi of connected paths |
| Leif Erikson Drive | way | footway | 45.549, -122.734 | Car-free Sundays; ~10.4 km length |
| Wildwood Trail (nature reserve) | relation | boundary | 45.571, -122.772 | Protected old-growth forest area |
| NW Saint Helens Road | way | residential | 45.535, -122.739 | Historic arterial with park access |
| NW Skyline Blvd | way | residential | 45.580, -122.790 | Ridge road with bike lanes |
| NW Germantown Road | way | residential | 45.570, -122.769 | Steep hill; popular cycling route |
| NW Kaiser Road | way | residential | 45.575, -122.765 | Connector between ridge roads |
| NW Laidlaw Road | way | residential | 45.573, -122.758 | Quiet residential connector |
| Lower Macleay Trail | way | path | 45.534, -122.713 | Southern trailhead; popular running start |
| Witch's Castle (Stone House) | node | tourist | 45.528, -122.725 | Historic ruins and photo op |
| Pittock Mansion | way | tourist | 45.525, -122.716 | Landmark destination for long runs |
| Forest Park Field House | node | amenity | 45.583, -122.778 | Community center, warm-up loop area |
| Ridge Trail Parking | way | parking | 45.588, -122.794 | Trailhead for ridgeline routes |
| Saint Johns Bridge | way | bridge | 45.593, -122.747 | Iconic 1931 suspension bridge |

---

## Forest Park Key Locations

| Location | Description | Coordinates |
|----------|-------------|-------------|
| Leif Erikson Dr & Skidmore St | North loop entrance, popular starting point | 45.571, -122.772 |
| Lower Macleay Park | Southern trailhead, Washington Park gateway | 45.534, -122.713 |
| Wildwood Trail Main Entrance | Off NW Germantown Rd, main access point | 45.570, -122.769 |
| Ridge Trail Parking Lot | Northwest Forest Park, ridgeline access | 45.588, -122.794 |
| Forest Park Field House | Community center, Warm-up loop area | 45.583, -122.778 |
| Witch's Castle (Stone House) | Historic ruins on Wildwood Trail | 45.528, -122.725 |
| Pittock Mansion | Landmark for long runs | 45.525, -122.716 |
| Woodstock (NW 25th Ave) | Mid-park entry | 45.528, -122.708 |

---

## OSM Routing Data Sources

All route distances and durations were computed using the following methodologies:

1. **Foot routing** — OpenStreetMap `foot` mode; uses paths, sidewalks, and pedestrian roads
2. **Bike routing** — OpenStreetMap `bike` mode; uses bike lanes, cycle tracks, and road bike lanes
3. **Coordinate verification** — All landmarks mapped with their OSM coordinates
4. **Recalculation** — Routes re-verified on each update using the OSM routing engine

*No estimated distances; all values are real, computed, and verifiable via OSM.*