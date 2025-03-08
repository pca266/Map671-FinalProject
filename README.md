# Map671-FinalProject

## Project Contents

- Data Source
- Project Background
- Purpose
- Mapmaking Process
- Map Summary
- Final Project Link

### Data Source  

The data from this project was sourced from these links: 

https://www.nrel.gov/gis/maps-marine 

https://www.boem.gov/renewable-energy/mapping-and-data/renewable-energy-gis-data 

https://catalog.data.gov/dataset/offshore-wind-turbine-locations-proposed-or-installed-de756 

### Project Background 

As an environmental studies student, I am very interested in things involving renewable energy. This is what inspired the creation of this map. 

### Purpose 

Offshore wind farming is a growing field. This map was created to show where wind farming is taking place, and where there are plans to possibly start the farming. I wanted to show their proximity to states so there are 30 mile radii around the wind turbines that are within 30 miles of a state. I was also curious about offshore's connections to waves so areas with waves of significant height are mapped as well.

### Mapmaking Process

- The filter process was used to get rid of irrelevant states. 
- The buffer feature was used to create radii of 30 miles around wind turbines. Then, the radii were filtered out so that only the ones that had a state within them remained.
- The distance to hub feature was used to show which wind farm was closest to each state.

### Map Summary 

Many offshore wind leases have not been built on yet and do not contain turbines. Also, even those leases that have been built on are not completed built on, with a decent amount of area open still.

Only two leases with turbines on them do not have a state within 30 miles of them. The rest do. 

It does not seem like waves of significant height effect where turbines are built. All leases are within this area of waves of significant height, which could lead you to believe that wave height has a positive impact on wind farming. However, since there are planning areas outside of the wave area, it can be inferred that wave height does not impact wind farming.

## Final Project Link
[index.html](index.html) 