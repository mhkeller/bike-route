Bike route
===

Mapbox GL JS example loading a Geojson linestring file, fitting it to bounds and allowing user geolocation. Useful for following bike routes such as those on the [Bike Hudson Valley](http://www.roberts-1.com/bikehudson/r/a/index.htm) website.

## Usage

Drop a GoeJson file of line string features into the root directory and call it `route.js`. Modify this file by adding `const geojson = ` to the beginning so we can use the `geojson` variable in the JavaScript.

Double-click `index.html` to open it in your browser.

## Preparing GoeJson files

Often, bike route files are in KML format. Uploda the file(s) [geojson.io](https://geojson.io) which will convert them to GoeJson. Sometimes routes require multiple KML files but no fear (!), [geojson.io](https://geojson.io) will append features to your existing collection. Save the file and you're all set.

## Dev

If you want a live server you can do `npm install` and `npm start` to get a quick live server.
