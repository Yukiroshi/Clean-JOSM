# <img width="32" alt="Icon" src="https://raw.githubusercontent.com/Yukiroshi/Clean-JOSM/refs/heads/main/logo_minimal.svg" /> All-in-one style for JOSM
!Style is still being developed, not all icons are nice! 

No more guessing which style will look good; this one looks better than good. Everything is nice to look at, while more complex at the same time.

# Fully working layer system

So You can see what is above or below without having to look into tags

# Rewritten and improved [Street lamps JOSM style](https://github.com/praszuk/josm-street-lamps-style) originally made by [NieWnen](https://github.com/praszuk)
<img width="360" alt="Lights showcase" src="https://github.com/user-attachments/assets/f6ce8e6e-664c-41bc-8557-24ea5d681d63" />

## Features:
- Adds a glowing circle around each lamp node
- Uses different colors depending on ```lamp_type```, ```light:method```, ```light:colour``` (currently only HTML or hex values)
or when ```light_source=warning```. ```light:colour``` has highest priority
- Throws a warning when ```lamp_type``` and ```light:method``` have different values
- Changes size based on ```light_source``` values (```floodlight```, ```signal_lamp```)
- Supports `light:count` and `light:direction` tags – renders multiple (up to 8) light points for a single lamp. If `light:direction` is missing, it falls back to default angles.

## Settings
Open JOSM's Advanced Preferences and type "Clean-JOSM". You can modify the following attributes:
- `light_glow_size` (default: 50)
- `light_glow_opacity` (from 0.0 to 1.0, default: 0.75)
- `light_point_size` (default: 40)
- `light_point_opacity` (from 0.0 to 1.0, default: 0.75)

# Rewritten and improved  [Direction Cones](https://github.com/tordanik/direction-cones-style) originally made by [tordanik](https://github.com/tordanik)
<img width="360" alt="Directions showcase" src="https://github.com/user-attachments/assets/0db4fbd7-7d31-433b-ba45-9992a7ea7442" />

## Features:
- Optimized cones are visible on every background
- Supports every correct ```direction``` and ```camera:direction``` value, up to eight directions simultaneously separated with a ```;```

## Settings
Open JOSM's Advanced Preferences and type "direction_cone". You can modify the following attributes:
- `direction_cone_opacity` (from 0.0 to 1.0, default: 0.75)
- `direction_cone_size` (default: 15)

# Multilingual `species` and `genus` support
<img width="360" src="https://github.com/user-attachments/assets/649d3f1c-583e-4ed2-ab53-373cbc9693e5" />

- Displays the `species:*` in JOSM app language
- When no such tag, displays `species`
- If no `species`, shows `genus` 

Made to easily browse and import natural monuments from various Geoportals
- [import ready GeoJSON](https://github.com/Yog/gdos_pomniki_przyrody_punktowe) from [GDOŚ](https://geoserwis.gdos.gov.pl/mapy/) for Poland by [Yog Sot](https://github.com/Yog)

# Improved [Incline](https://josm.openstreetmap.de/wiki/Styles/Incline) originally made by [Klumbumbus](https://github.com/Klumbumbus)

And also parts of [Bench](https://josm.openstreetmap.de/wiki/Styles/Bench)

# Much nicer icons (at least some of them)
Changed icons are from [MakiMaki](https://github.com/Yukiroshi/MakiMaki), where every icon is an improved and coloured version from Maki, Temaki or OSM Carto. When needed, additional icons are created from scratch by me.

Roof icons by [Mxdanger](https://github.com/mxdanger)

# All settings
Open JOSM's Advanced Preferences and type "Clean-JOSM". You can modify the following attributes:
- General display
  - `scaling` (default: 1) - general scaling multiplier
  - `font` (default: Bahnschrift) - font used to display text
  - `high_contrast` (default: false) - slightly widens all ways and enlarges nodes, may not work properly
  - `round_symbols` (default: true) - makes nodes more pleasing to the eye
  - `clean_view` (default: true) - utilises more zoom rules to hide stuff, best for POI mapping and micromapping 
  - `highway_labels` (default: true) - displays labels on named highways
  - `place_fill_colour` (default: false) - fills areas tagged as `place=*`, cities, villages etc.
  - `partial_fill` (default: true) - only displays fill close to edges, good for almost every use
  - `surface` (default: true) - makes outlines of ways dashed based on surface
- Cones and arrows
  - `direction_cone_opacity` (from 0.0 to 1.0, default: 0.75) - opacity of direction cones and arrows
  - `direction_cone_size` (default: 15) - size of direction cones and arrows
- Lights
  - `light_glow_size` (default: 50) - size of big circles under `highway=street_lamp` and `light_source=*`
  - `light_glow_opacity` (from 0.0 to 1.0, default: 0.75) - opacity of big circles under `highway=street_lamp` and `light_source=*`
  - `light_point_size` (default: 40) - size of small points around `highway=street_lamp` and `light_source=*`
  - `light_point_opacity` (from 0.0 to 1.0, default: 0.75) - opacity of small points around `highway=street_lamp` and `light_source=*`
- Railways
  - `railway_maxspeed` (default: false) - displays maxspeed values and adds colors even to unused/abandoned/construction/proposed rails
  - `railway_icons` (default: false) - displays more advanced variants of railway icons (only some for now)
- Validation
  - `warnings` (default: true) - displays serious errors and makes them hard to miss (without obstructing view)
  - `notices` (default: true) - displays possible mistakes or suggestions
  - `highlight_buildings` (default: false) - used mainly for importing buildings in Poland using plbuildings plugin

# Installation

- Open JOSM settings panel (`F12`),
- then look for <img width="20" src="https://josm.openstreetmap.de/browser/trunk/resources/images/dialogs/mapstyle.svg?format=raw"/> Map Paint Styles
- type `Better JOSM` (or author name, `Yukiro`) in the search box
- click on it
- then click on the <img width="20" src="https://josm.openstreetmap.de/browser/trunk/resources/images/preferences/activate-right.svg?format=raw"/> blue arrow between the available and active styles:


- make sure to disable JOSM internal style and any other styles, which are merged into this one, otherwise there might be a mess!
- don't forget to click <img height="20" src="https://github.com/user-attachments/assets/7a722b4e-fc73-4b8e-86c7-39e1f6726537" /> OK button at the bottom, otherwise it won't save changes!

Alternatively:

See [installation instructions from official JOSM website](https://josm.openstreetmap.de/wiki/Help/Preferences/MapPaintPreference).
