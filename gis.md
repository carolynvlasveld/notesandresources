# GIS

### Learning about projections

Quick video explaining the concept: [Why all maps are wrong](https://www.youtube.com/watch?v=kIID5FDi2JQ)

Cool map of the Gall–Peters projection, image by (Daniel R. Strebe, Wikimedia Commons), showing countries with more accurate relative areas than the commonly used Mercator projection (used by Google maps because it preserves shape and makes it easier to navigate at small scales) but with more distorted shapes (note how big the continents are in the southern hemisphere relative to the northern):

![Gall–Peters projection](https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Gall%E2%80%93Peters_projection_SW.jpg/1920px-Gall%E2%80%93Peters_projection_SW.jpg)

There are heaps of other projections. Also the Winkel tripel projection that is like a balance between Mercator and Gall-Peters

Also cool: https://truesizeofcountries.com/

---

Interesting and worth checking out: https://mapartists.org/


---


For QGIS, check out: https://www.youtube.com/@MattForrest


Questions/revisions: how does a raster tiff, etc, 'know' where it goes in the map? If it's just a simple bunch of pixels, where is the information storeed in the tiff file telling it where (i.e.,m the coords) it belongs on a map?

Shape'files' should have at least 3 files ot them: .shp (main shapefile), .shx, and .dbf (attrivbute table-can be opened in excel/calc/etc). if .prj file is there, it will have projection info for the layer

---

Written by [Carolyn Vlasveld](https://carolynvlasveld.github.io/)
