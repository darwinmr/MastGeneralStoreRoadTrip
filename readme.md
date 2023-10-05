# "The Tastiest Road Trip in Western NC" (A road trip that reaches every Mast General Store in North Carolina)

#### Route map

---

This web map delineates a trip from Winston-Salem, NC to the North Carolina and Tennessee border on I-40. Instead of a straight path along interstates, this map includes each Mast General Store location in the state of North Carolina. In Google Maps, a route was drawn with each Mast General Store location selected as a location along the route. This map was converted to a GPX file using the open-source tool [(Maps to GPX)](https://mapstogpx.com/). Next, using another open source tool [geojson.io](http://geojson.io) the GPX file was converted to a geoJSON file which contained the addresses and names of each stop; it was then loaded into VSCode as a javascript file. Using [Leaflet](https://leafletjs.com/) JavaScript library, the geoJSON features were displayed through two functions. These two geometry types were "LineString" and "Point" geometry types from the GeoJSON. 