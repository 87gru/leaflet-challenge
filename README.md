# leaflet-challenge

![BasicMap](Leaflet-Part-1/Images/2-BasicMap.png)

[Click here to view the Earthquake Map!](Leaflet-Part-1/index.html)

## Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Steps
- Dataset acquired from from USGS geojson (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- Import and visualize the data by doing the following:
    - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
    - Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
    - Include popups that provide additional information about the earthquake when its associated marker is clicked.
    - Create a legend that will provide context for your map data.

## Included in Repository
- README.md
- Leaflet-Part-1
    - `index.html`
    - Images directory
    - static directory
        - css directory
            - `style.css` contains formatting for legend
        - js directory
            - `logic.js` contains majority of code

## Resources
To match the grayscale map in the example on the BootCamp website, I used a script written by Ilya Zverev, located here: https://github.com/Zverik/leaflet-grayscale
