# Within Reach? Park Access Across Manhattan

An interactive geospatial analysis of park accessibility in Manhattan, modeling walkable access to green space using buffer-based spatial analysis.


## Overview

This project explores how accessible parks are across Manhattan by estimating 5-minute walking distances from park locations and visualizing cumulative coverage zones.


## Methodology

- NYC Parks dataset filtered to Manhattan  
- Park geometries converted into polygons  
- 400-meter buffers applied (~5-minute walk)  
- Buffers merged to estimate accessibility coverage  
- Interactive map built using Folium  


## Key Insight

Park access in Manhattan is shaped by a few large anchor parks, which generate broad coverage zones, while smaller parks create more fragmented access across dense neighborhoods.


## Interactive Map

[View the map](map.html)


## Files

- `manhattan_park_accessibility.ipynb` — full analysis  
- `map.html` — interactive visualization  
