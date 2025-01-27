In this challenge, I managed to create the Earthquake Visualization after getting dataset from the USGS website. I used the dataset of the past 7 days.
the URL were used by the JSON to pull in the data for visualization.
In a javascript file, I create different functions such as:
- Styleinfo for returns the style data for each of the earthquakes.
- getcolor to determine the marker's color based on the earthquake's depth.
- getRadius determines the radius of the earthquake marker based on its magnitude.

I used the loop to generate a label with a colored square for each interval. In addition, I added a GeoJSON layer to the map once the file was loaded and also created a popup for each marker to display the magnitude and location of the earthquake after the marker had been made and styled.