# CensusDataVis
Visualizing Census Data on the state and county levels. As well as displaying city data from a json file

You can select what data you would like to view from the dropdown menu

Use the slider to adjust the state opacity

The top left chart is a histogram showing data from each of the states, hovering over a state highlights it green the chart.

The bottom left chart is another histogram charting counties in the state you are hovering, hovering over a county also highlights it green in the chart.

A tooltip pops up when highlighting states or cities and provides you with data.

Census Information was aquired from the American Community Survey 3 Year Data API found here:
http://www.census.gov/data/developers/data-sets/acs-3year.html

I based my map off of Mike Bostocks D3 example found here:
https://bl.ocks.org/mbostock/4090848

Data on the cities was found here:
https://gist.github.com/Miserlou/c5cd8364bf9b2420bb29#file-cities-json
