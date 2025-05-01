---
title: "{{ replace .Name "-" " " | humanize }}"
date: {{ .Date }}
draft: false
category: "Checkin"  # Personal location updates
tags: [""]
location: ""  # Location name (e.g., "Café de Paris")
mapCoordinates: ""  # Latitude,longitude (e.g., "48.8584,2.2945")
---

TRY:
The OSM URL format is https://tile.openstreetmap.org/<latitude>/<longitude>/<zoom>/<width>x<height>.png. Adjust 15 (zoom) and 800x400 (size) as needed.