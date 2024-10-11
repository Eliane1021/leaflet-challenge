# leaflet-challenge
#Instructions
The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualization

Part 2: Gather and Plot More Data (Optional with no extra points earning)

##Part 1: Create the Earthquake Visualization
![image](https://github.com/user-attachments/assets/4e8ca66f-eb7d-4576-93ec-8b7757bbf3ef)


Your first task is to visualize an earthquake dataset. Complete the following steps:

Get your dataset. To do so, follow these steps:

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:
![image](https://github.com/user-attachments/assets/b261831a-61dc-4c37-b64e-15aa41b22bf4)


When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:
![image](https://github.com/user-attachments/assets/8a21c506-7939-4fba-b973-8cb242fb80d6)


Import and visualize the data by doing the following:

Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

Hint: The depth of the earth can be found as the third coordinate for each earthquake.

Include popups that provide additional information about the earthquake when its associated marker is clicked.

Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map.

##Part 2: Gather and Plot More Data (Optional with no extra points earning)
Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplatesLinks to an external site..

This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.

The following image is an example screenshot of what you should produce:

![image](https://github.com/user-attachments/assets/5db9e3cc-2988-48e7-8df9-7203e21327ab)


