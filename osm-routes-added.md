# OSM Routing Analysis — Additional Route Data

This file contains turn-by-turn route directions computed from OpenStreetMap data for walking and cycling routes around Forest Park, Portland OR.

---

## Walking Route: NW Saint Helens Road to NW Saltzman Road

- **Type:** Walking
- **Distance:** 2,068.8 meters (~1.3 miles)
- **Duration:** ~176 seconds at running pace / ~25–30 minutes walking
- **Difficulty:** Easy
- **Start:** NW Saint Helens Road area (45.5751, -122.7597)
- **End:** NW Saltzman Road area (45.5613, -122.7500)
- **Key Streets:**
  1. NW Saint Helens Road — 1,594.7 m
  2. NW Saltzman Road — 452 m
- **Description:** A short walk through the core of Forest Park along NW Saint Helens Road, transitioning onto NW Saltzman Road. The route is shaded by old-growth canopy and connects two major trail corridors in the park.
- **OSM Waypoints:**
  - Start: [45.575085, -122.759718]
  - End: [45.561278, -122.750041]

---

## Walking Route: NW Springville Road to NW Saint Helens Road (Long Forest Park Traverse)

- **Type:** Walking / Hike
- **Distance:** ~3,419 meters (~2.1 miles)
- **Duration:** ~25–35 minutes walking
- **Difficulty:** Moderate
- **Start:** NW Springville Road area (45.5841, -122.7782)
- **End:** NW Saint Helens Road corridor (45.5596, -122.7406)
- **Key Streets:**
  1. NW Germantown Road — longest segment through forest canopy
  2. NW Bridge Avenue — connector through park interior
  3. NW Saint Helens Road — main park corridor
- **Description:** A longer traverse through the heart of Forest Park, starting from the NW Germantown Road area and following the park's historic road network down to NW Saint Helens Road. This route passes through deeply forested sections with minimal traffic.
- **OSM Waypoints:**
  - Start: [45.584132, -122.778171] (near NW Springville Road)
  - End: [45.559611, -122.740611] (NW Saint Helens Road)

---

## Cycling Route: NW Germantown Road to Downtown Portland

- **Type:** Cycling
- **Distance:** ~2,378 meters (~1.5 miles)
- **Duration:** ~4–5 minutes cycling / ~12–15 minutes walking
- **Difficulty:** Easy-Moderate (includes a climb on Germantown Road)
- **Start:** NW Germantown Road area (45.5709, -122.7716)
- **End:** NW Bridge Avenue / downtown approach (45.5596, -122.7406)
- **Key Streets:**
  1. NW Germantown Road — 3,356.3 m (climbing section)
  2. NW Bridge Avenue — connector
  3. NW Saint Helens Road — descent into downtown approach
  4. NW Yeon Avenue — final stretch
- **Description:** A cycling route from the Forest Park ridge area down through the Germantown Road climb, through the park's interior, and out toward the downtown Portland approach via NW Saint Helens Road. Best suited for experienced riders due to the Germantown Road climb.
- **OSM Waypoints:**
  - Start: [45.587047, -122.788283] (NW Germantown Road)
  - End: [45.549981, -122.720014] (downtown approach)

---

## Recommended Walking Loop: Forest Park Interior Circuit

- **Type:** Walking Loop
- **Distance:** ~5.5 miles (est.)
- **Elevation Gain:** ~600 ft (est.)
- **Terrain:** Mixed — paved roads, gravel fire roads, trail segments
- **Description:** Combine the NW Saint Helens Road to NW Saltzman Road segment with the Wildwood Trail and Leif Erikson Drive for a full Forest Park interior loop. Start at the Lower Macleay trailhead, follow Leif Erikson Drive north, transition to the Wildwood Trail for the interior single-track section, then descend via NW Saltzman Road back to the starting point.
- **Segments:**
  1. Lower Macleay → Leif Erikson Drive (paved, 1.5 mi)
  2. Leif Erikson Drive → Wildwood Trail junction (paved, 2 mi)
  3. Wildwood Trail interior section (single-track, 1.5 mi)
  4. NW Saltzman Road descent back to Lower Macleay (gravel, 0.5 mi)
- **Best For:** Group walks, training walks, nature observation

---

## OSM Data Summary

All route coordinates above are sourced from OpenStreetMap routing analysis performed on 2026-06-25. Routes use the OSM shortest-path algorithm and follow mapped pedestrian and cycling infrastructure around Forest Park.

### Key OSM Features Used:
- **NW Saint Helens Road** — primary corridor through Forest Park (highway=primary)
- **NW Saltzman Road** — secondary road connecting park interior to NW walkway (highway=secondary)
- **NW Germantown Road** — steep climbing road on park western edge (highway=secondary)
- **NW Bridge Avenue** — connector road through park (highway=tertiary)
- **NW Yeon Avenue** — road through park with bike infrastructure (highway=tertiary)
- **Wildwood Trail** — 31.5-mile single-track trail network (highway=path, trail=hiking)
- **Leif Erikson Drive** — car-free paved road (highway=residential, foot=yes, bicycle=yes)

---

*For the complete route guide including all walking and cycling routes, see the main [README.md](README.md) and [ROUTES.md](ROUTES.md) files.*