# Historical Cheeseman Park

**July 2020** · Cheeseman Park and its immediate surroundings, Denver, Colorado

How did the layout and use of the park change over time? This digital archaeology exercise overlays a hand-drawn historical map on a modern map so readers can compare the two.

[Open the interactive map](https://tom-shanks.github.io/Historical_Cheeseman/). Use **Layers** to toggle the historical raster and the reference basemap independently.

## Sources and methods

- The original [historical raster](data/cheeseman_1950_modified_1.png) and its sidecar are preserved in this repository. The original repository metadata listed Denver Public Library Digital Collections item 2662 as a source lead. The old catalog URL no longer resolves reliably, and the map's creator, exact date, and reuse terms need confirmation. The filename is the evidence for the circa-1950 label.
- Tom Shanks georeferenced the hand-drawn layout against contemporary imagery and published the overlay, as described in his [original portfolio](https://tom-shanks.github.io/). QGIS and qgis2web produced the web export, and Leaflet provides pan, zoom, and layer controls.
- The reference map in the revised export is [OpenStreetMap](https://www.openstreetmap.org/copyright). The original overlay bounds and raster are preserved.

The archive contains the published raster and its geographic display bounds. Control points, transformation settings, and alignment error were not recorded in the export. Use it for visual comparison. The transferable work is registering a raster to a spatial reference, publishing it with traceable inputs, and distinguishing alignment from measurement accuracy.
