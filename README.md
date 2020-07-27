# Mapping
Set of resources and projecs about maps

# QGIS

1- [Introduction](https://www.youtube.com/watch?v=kCnNWyl9qSE)

- Generate a world map: Coordinate - world
- Slow Zoom: zoom + ctrl
- Full map: ctrl + shift + F
- Projection on the bottom-right: it's the method that QGIS uses to stretch the map
  - Change the projection will change the map and it's properties such as the coordinates
    - 3857 - pseudo mercator : coordinates are points from the mouse over the map
    - 4326 - wGS : coordinates are degrees/ this is oriented to local projections
      - 326 for northern hemysphere and search a zone
    - If you don't want to deal with local projections choose wsg pseudo mercator   
- In the browser/XYZ tiles you can add OpenStreetMap to your map
- A convenient way to experiment with data is to create a temporary scratch layer, which will be deleted when the program session extinguish.
  - By defaul it is created in edit mode
  - You can edit it drawing polygons and editing them. 
  - Don't forget to save changes in temporary layers or/and converting them in permanent