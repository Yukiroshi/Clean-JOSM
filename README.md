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
- `base_circle_glow_size` (default: 50)
- `base_circle_glow_opacity` (from 0.0 to 1.0, default: 0.75)
- `light_point_icon_size` (default: 40)
- `light_point_icon_opacity` (from 0.0 to 1.0, default: 0.75)

# Rewritten and improved  [Direction Cones](https://github.com/tordanik/direction-cones-style) originally made by [tordanik](https://github.com/tordanik)
<img width="360" alt="Directions showcase" src="https://github.com/user-attachments/assets/0db4fbd7-7d31-433b-ba45-9992a7ea7442" />

## Features:
- Optimized cones are visible on every background
- Supports every correct ```direction``` and ```camera:direction``` value, up to eight directions simultaneously separated with a ```;```

## Settings
Open JOSM's Advanced Preferences and type "direction_cone". You can modify the following attributes:
- `direction_cone_opacity` (from 0.0 to 1.0, default: 0.75)
- `direction_cone_size` (default: 10)

# Improved [Incline](https://josm.openstreetmap.de/wiki/Styles/Incline) originally made by [Klumbumbus](https://github.com/Klumbumbus)

And also parts of [Bench](https://josm.openstreetmap.de/wiki/Styles/Bench)

# Much nicer icons (at least some of them)
Changed icons are from [MakiMaki](https://github.com/Yukiroshi/MakiMaki), where every icon is an improved and coloured version from Maki, Temaki or OSM Carto. When needed, additional icons are created from scratch by me.

Roof icons by [Mxdanger](https://github.com/mxdanger)

# Installation
[Installation instructions](https://josm.openstreetmap.de/wiki/Help/Preferences/MapPaintPreference) from official JOSM website

# General settings
Open JOSM's Advanced Preferences and type "Clean-JOSM". You can modify the following attributes:
- `scaling` (default: 1)
