# NM Vehicle Accidents — Galisteo area

An interactive map of vehicle crashes on the roads around Galisteo, New Mexico,
with road segments color-coded by **fatal-crash rate** (fatal crashes per 100
million vehicle-miles driven), so volume is accounted for — not just raw counts.

**Live map:** https://tedalcorn.github.io/NM-vehicle-accidents/

## What's shown
- **Road segments** colored by fatal-crash rate (green = low, red = high).
- **Fatal crashes 2008–2024** (red dots) — click for date, type (e.g. bicyclist,
  rollover), and whether alcohol was involved.
- **Serious/injury crashes 2012–2016** — a partial layer, toggled off by default.

## Sources
- **Fatal crashes:** NHTSA Fatality Analysis Reporting System (FARS), 1975–2024.
  Reliable coordinates begin ~2008, so the map plots 2008 onward.
- **Traffic volume & serious-injury crashes:** New Mexico DOT (public ArcGIS).

## Caveats (read before drawing conclusions)
- Per-segment fatal-crash rates rest on **small numbers** — read them case by case
  (each segment's raw count is in its popup), not as precise estimates.
- Rates use **2024 traffic counts** against a 2008–2024 crash window, so they don't
  adjust for how traffic changed over time.
- County/local roads (e.g. CR 42) carry only a **placeholder traffic count**, so
  they're left off the rated network; crashes on them still appear.
- U.S. average fatal-crash rate ≈ 1.3 per 100M vehicle-miles, for reference.
