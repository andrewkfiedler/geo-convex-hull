geo-convex-hull
===========
This module provides a function to determine the convex hull for a set of geographical coordinates (latitude and longitude).  Units should be in degrees.

The return value is an array of latitude and longitude coordinates.

# Example

```javascript
var calculateConvexHull = require('geo-convex-hull')

var points = [
  {
    latitude: 33.4255,
    longitude: -111.9400
  }, 
  {
    latitude: 43.6187,
    longitude: -116..2146
  },
  {
    latitude: 39.8066,
    longitude: -101.0421
  }
]

var convexHull = calculateConvexHull(points);

```

# Attribution
Taken with minimal modifications from here:
https://github.com/Leaflet/Leaflet.markercluster/blob/master/src/MarkerCluster.QuickHull.js