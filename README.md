# Visualizing-Data-with-Leaflet

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

# Your Task

# Level 1: Basic Visualization
<img width="896" alt="Screen Shot 2019-08-23 at 11 08 08 AM" src="https://user-images.githubusercontent.com/49076702/63613766-5696cb00-c596-11e9-948e-90fb9f825c41.png">

Your first task is to visualize an earthquake data set.

# 1) Get your data set
<img width="898" alt="Screen Shot 2019-08-23 at 11 09 35 AM" src="https://user-images.githubusercontent.com/49076702/63613888-9198fe80-c596-11e9-8637-2ad530fa68e7.png">

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

# 2) Import & Visualize the Data

Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

- Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes   should appear larger and darker in color.
- Include popups that provide additional information about the earthquake when a marker is clicked.
- Create a legend that will provide context for your map data.
- Your visualization should look something like the map above.

# Level 2: More Data (Optional)

