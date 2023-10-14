# Mapping

This is an HTML document that creates a map animation using Mapbox GL JS. Here's a description of its components:

Steps to run the code:

 step 1. HTML Structure:
   - The document starts with the usual HTML5 structure, including the <!DOCTYPE html> declaration.
   - It includes the necessary meta tags and external scripts and stylesheets for Mapbox GL JS.

 step 2. CSS Styles:
   - The CSS styles in the <style> section define the appearance of the map and a button overlay.
   - The map is set to fill the entire viewport, and a button is placed at the top of the map.

step 3. JavaScript:
   - The JavaScript code initializes a Mapbox GL JS map and places it inside a <div> element with the id "map".
   - A marker is added to the map at the coordinates [76.98401, 11.01151].
   - The move() function is defined to animate the movement of the marker along a predefined set of bus stops (busStops array).
   - The move() function is called initially to start the animation.
   - The animation updates the marker's position every 1000 milliseconds (1 second) to simulate the bus moving from one stop to another.

step 4. Mapbox Access Token:
   - The Mapbox access token (mapboxgl.accessToken) is provided. You would typically replace this with your own Mapbox access token.
    
Future Improvements

Overall, this HTML document creates an interactive map with a button that triggers an animation showing the movement of a marker (simulating a bus) between specified bus stops on the map. The animation uses Mapbox GL JS for mapping functionality.
