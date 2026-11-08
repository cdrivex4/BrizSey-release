# BrizSey Release Candidate Changelog 📜

### v1.2.0 (Build #45 - RC1) - 2026-11-08
- **Dedicated Public Release Candidate Identity**: Public build now displays as `BrizSeyRC1` upon installation to clearly delineate the official release candidate channel.
- **SWIO Tropical Cyclone & Storm Surveillance**: Integrated real-time tracking for South-West Indian Ocean tropical depressions, storms, and cyclones sourced from RSMC La Réunion and JTWC, complete with category badges, central pressure, peak wind gusts, and multi-day forecast cones.
- **Dynamic Relative Storm Vector HUD & Granular GPS Centering**: Granular one-shot GNSS fix pinpointing user location with a pure CSS pulsing halo and computing relative closing velocity towards approaching storms.
- **Decision-Theoretic Cost-Loss Alerting Engine**: Calibrated 4-persona alert filtering matrix (Fisherman, Farmer, Tourism, Commuter) based on World Bank Working Paper 11407 to eliminate false-alarm fatigue.
- **Meteorological Bulletin Expiration Engine**: Resolved RFC 1123 vs ISO 8601 timestamp parsing bug; expired weather bulletins are automatically filtered from active warnings.
- **GitHub Community Bug Tracker**: Centralized public issue tracking and community feedback through the [BrizSey-release Issue Tracker](https://github.com/cdrivex4/BrizSey-release/issues).

### v1.2.0 (Build #18) - 2026-09-23
- **Scenic Landscape Background Overhaul**: Added 3-layer scenic depth featuring azure/midnight sky, turquoise ocean with glinting wave rhythms, granitic island horizon, emerald coastal bluff with dense swaying grass blades, and a living dandelion clock with drifting seeds.
- **Sunny Day Seychelles Butterfly Animation**: Vector-rendered Seychelles Citrus Swallowtail that flutters in from the right, perches on the living dandelion clock, and flies off to the left on sunny days.
- **Plain-English Terminology**: Simplified astronomical terms (*First Light / Last Light*) and radar tracker terminology (*Live Rain Radar & Front Tracker, FRONT SPEED, RAIN DISTANCE, MOUNTAIN SHIELD*).
- **1-Tap Section Reordering**: Added Move Up (▲) and Move Down (▼) buttons and drag handles in Layout Edit mode.

### v1.2.0 (Build #16) - 2026-09-22
- **Living Dandelion Clock**: Introduced wind-reactive dandelion clock and drifting feathery pappus seed particles.
- **Ocean Wave Horizon**: Sinusoidal ocean wave surface with specular light trails.

### v1.2.0 (Build #15) - 2026-09-22
- **Live Observation Accuracy**: Synchronized temperature, humidity, and atmospheric conditions with live SMA observations.
- **Back Navigation**: Fixed system and gesture back navigation across settings and radar screens.

### v1.2.0 (Build #14) - 2026-09-22
- **100% Free Open Basemaps**: Switched WebGIS to Esri World Topographic, Esri Satellite Hybrid, and OpenTopoMap (no API keys required).
- **WebGIS Opacity Slider**: Real-time layer opacity blending for Doppler radar and EUMETSAT cloud overlays.
