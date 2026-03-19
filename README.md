# Faith-based Affordable Housing Developments (2015-2025)
This map visualizes the 200 developments collected in the database on faith-based affordable housing and shelter, led by Dr. Nadia Mian at the Voorhees Center for Civic Engagement. More details can be found by clicking [this link](https://rwv.rutgers.edu/fbah/). 

<iframe src="InteractiveWebmapFB.html" height="855" width="95%"></iframe>
All 200 developments in the database (as of December 2025) are included in this map. These developments were cleaned extensively and geocoded using ArcGIS geocoder in Python, and visualized using the folium library. The pattern of faith-based housing developments being constructed can be visualized using the timeline slider, which populates the developments by year*. The construction time data was cleaned to bring it to a visualizable format in folium’s timeline slider tool. 

Clicking on each development reveals a small popup which provides information on:
- The project name
- The congregation name and denomination/religion
- The year the project was completed
- The type of housing
- The project size
- The developer’s name
- If the property has a historic status
- The project description

Statewise trends can be toggled on/off, in the upper right-hand corner of the map. They provide information on the rent-burdened population, the status of YIGBY law implementation**, and the number of developments in each state. Hovering over each feature reveals information on each trend. These datasets were prepared from the static maps.

The basemap can also be switched between a simple Carto Positron basemap and Open Street Map, which can be helpful to examine other local features if you zoom into the basemap.

<em>*4 developments’ opening dates have not been identified. They populate in the final year of the timeline slider, 2025. **As per December, 2025.</em>
