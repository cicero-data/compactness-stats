# compactness-stats

See the [wiki](https://github.com/cicero-data/compactness-stats/wiki) page for more information on methodology and sources.

### Data Dictionary

| Field Name  | Description |
| ------------- | ------------- |
| STATEFP  | State FIPS code  |
| STATE  | State abbreviation |
| SLDUST or SLDLST  | State legislative district code  |
| GEOID | Census geoidentifier, a concatentation of the state FIPS code and state legislative district code  |
| NAMELSAD | Current name of the legal/statistical (district) descriptionfor state legislative district chamber  |
| Area | Area of the district in square meters  |
| Perimeter | Perimeter of the district in meters  |
| Polsby-Popper | Polsby-Popper ratio score  |
| Schwartzberg Radius | Calculated to generate the Schwartzberg score, radius of a circle with an area equal to that of the district  |
| Schwartzberg Perimeter | Calculated to generate the Schwartzberg score, perimeter of a circle with an area equal to that of the district  |
| Schwartzberg | Schwartzberg ratio score  |
| Convex Hull Area | Calculated to generate the Convex Hull score, area of the convex hull polygon containing the district  |
| Area/Convex Hull | Area/Convex Hull ratio score  |
| MBC Area | Area of minimum bounding circle of the district in square meters  |
| Reock | Reock ratio score  |
