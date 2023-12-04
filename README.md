# cours_CSMM_23-24
Here we share the code for the course at CentraleSupélec, Case Study of Mobility Modelling, year 2023-2024
1. In the first session, the aim is to get familiar with the region that you work on. Some simple calculations are made  such as mean distance, number of commuters and mode share. In the example, I am using the data on the IDF region in France.
2. In the second session, the aim is to locate the origin of the commuters, especially the outsiders (who are generally long-distance commuters). We first get the Excel file of the main origin cities, with the flow and distance.

![image](https://github.com/liangkangenpc/cours_CSMM_23-24/assets/82210230/dad3f254-a32e-471d-8c44-3ac7b68fb431)

Then we make a histogram from this data. 

Secondly we shall project the rail and road network with OSM basemap. 
![image](https://github.com/liangkangenpc/cours_CSMM_23-24/assets/82210230/61120051-f6b5-46bf-aff9-8053d54e5739)

3. In the third session, after obtaining the OD file with the histogram, we are able to calculate the distance and time for each OD, given the time of departure. For example, departing from Noisy-Champs to CIRED at the current time, it generates:

![car_route_map](https://github.com/liangkangenpc/cours_CSMM_23-24/assets/82210230/a6d8b354-9a2d-4b8e-9443-2a2518362f91)

The result: 
Noisy - Champs, Rue des Hauts Châteaux, 93160 Noisy-le-Grand, France ==>  94736 Cédex, 45bis Av. de la Belle Gabrielle, 94130 Nogent-sur-Marne, France.

distance:  12.1 km, traveling Time:  20 mins
