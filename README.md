# 3D-4DGIS-Project
# Karlsruhe Palace Visualization
This project is a 3D and 4D GIS visualization of the Karlsruhe Palace, created using CesiumJS. t provides an interactive map with the help of which a user can explore the palace and its surroundings with detailed 3D representations and historical information.
# Features
3D Visualization: Utilizes CesiumJS to render a realistic 3D model of the Karlsruhe Palace.

Interactive Map: one can interact with the map, including zooming, panning, and rotating to view the palace from different angles.

Historical Information: Displays a detailed description of the Karlsruhe Palace, including its history, location, and current use.

Entity Highlighting: Highlights the palace outline and provides a description when the entity is selected.

Camera Control: Sets the initial camera view to focus on the Karlsruhe Palace and provides functionality to fly to the palace when selected.
# Technical Details
CesiumJS: The project leverages CesiumJS, a JavaScript library for creating 3D globes and maps.

Imagery Provider: Uses Cesium Ion Imagery Provider with asset ID 2 for the base map.

Entity Definition: Defines the outline and extruded height of the Karlsruhe Palace using Cartesian coordinates.

Material and Outline: The palace polygon is styled with a semi-transparent yellow material and a black outline.
# How to Run
Clone the repository to your local machine.

Run the file in your IDE (Pycharm/ VS Code) or open the index.html file in a web browser (Firefox for best results).

Interact with the 3d visualisation of the Karlsruhe Palace on the map.
