# Google Geomap API

This contains the use of google's GEOMAP API in python. We need to take in the data from the where.data
which has the locations to be plotted on the map which can be seen on the where.html file.
The geoload.py takes in the location from the API and puts it on the database. Then the geodump.py
takes this database and then dumps it into the where.js JavaScript file to be visualized by the html file.