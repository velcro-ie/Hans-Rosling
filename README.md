# Hans-Rosling

Information Visualisation
Channelling Hans!

1 What Is the Purpose of Your Visualisation?
Do continent tend to have the same government type?
Is the government type of country dictated or influenced by the continent and neighbours of a country. Do certain areas of the planet have a higher concentration of republics or monarchies? The best way to view this is on a map.
There are several different data sources for the government types of countries and they all appear to have different classification types. For the purposes of our visualisation I will use the dataset provided for the Hans Rosling assignment.
2 What Similar Visualisations Exist?
A lot of similar visualisations exists. There is on Wikipedia and on the CIA site. These are both are sites that I looked at getting a new dataset from. A google image search for world government types there are a lot of results. Some of these are maps for sale and others are web sites containing the maps.
These visualisations often use different types of maps, colour coding’s and data sources. Each example of the map uses their own data sets.
3 Why Is Your Visualisation A Good Solution?
The question that we are asking the data is best seen on a choropleth map. It makes it very easy for the viewer to identify where the government types are placed in the world.
I used colour brewer to get 12 of the colours that I needed. The extra three I made up based on the colours that were in the colour brewer pallet.
In my visualisation I have grouped the government types 6 broad categories and gave each of these a colour. The sub categories within these categories are then shades of the colour.
1) Political republics
a. socialist republic
b. people's republic
2) federal republic
a. federation
b. federal republic
c. presidential federal republic
d. parliamentary federal republic
3) republic
a. republic
b. parliamentary republic
4) monarchy
a. monarchy
b. constitutional monarchy
c. parliamentary monarchy
d. absolute monarchy
5) Islamic republic
a. Islamic republic
b. Islamic-socialist people's republic
6) autonomous region of another country
This allows the government types to be seen much more easily. The legend is also split into these categories to make it easier for the viewer to identify the groups.
4 What Data Manipulation Was Required To Create Your Solution?
The dataset used for the map was the one given to us for the assignment. There were several other data sets that I could have chosen to use with each dataset using a different government classification system. I chose the gapminder set as it had a manageable number of government types. The other datasets had from four to twenty four different government types and required a lot of cleaning of the data.
In the gapminder data set each country only has one government type. There are 17 government types in the file. I merged "territory of the United States", "autonomous region of Denmark" and "autonomous territory of the Netherlands” into “Foreign territories of another country” to reduce this to 15.
This merge was done in the JavaScript code so as not to change the original dataset at all. Due to the nature of the data the government types had to be hard coded in the JavaScript.
5 What d3 Resources Did You Use To Create Your Visualisation?
I used the d3.geomap to display the map. The map is a zoomable choropleth map.
The geomap has a three digit country code so I needed to change the two digit country code from the data set into its three digit equivalent. I did this in the JavaScript code so as not to change the original dataset.
I used the colour brewer site to get 12 of the colours used in the map and added the extra three based on what was already there.
