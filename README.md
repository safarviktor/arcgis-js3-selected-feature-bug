# arcgis-js3-selected-feature-bug

When I select a feature on a zoomed-out map and then zoom in, the selected feature still has the generalized geometry from when the map was zoomed out. All other features in the layer get their geometry recalculated. If I unselect the feature and trigger a zoom-end event, the geometry of that feature gets recalculated again.

https://community.esri.com/t5/arcgis-javascript-maps-sdk-questions/selected-feature-s-generalized-geometry-does-not/m-p/1244853#M79758

https://youtu.be/k8CHvYJ19hw
