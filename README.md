# openData
Repository of open data of citychrone framework

### Data format
for each city in the folder data/city_accessibility_quantities/ there a name_city.zip file. The zip file contains a json file contaning a list of elements. Each element contains the information relative to an hexagon of the corresponding city. The fields of each elements are: 

| Fields        | content          
| ------------- |:-------------|
| city          | city name     | 
| hex      | geojson of the hexagon      | 
| point | geojson of the center of the hexagon      |
| pop | population      |
| socialityScore | sociality score computed at different hour (expressed in second) of a typical working day   |
| velocityScore | velocitity score computed at different hour (expressed in second) of a typical working day   |
| tSocDist | time distance from the point with highest value of sociality score      |
| tVelDist | time distance from the point with highest value of velocity score      |
