# Page Ranking algorithm and Visualization 

This consist of the page ranking algorithm taught in dr.chucks course. 
The spider.py retrieves the pages from the specific URL given and the sprank.py
runs the pageranking algo on the retrived links. The spider.py further checks for 
links in thesame page and then updates the found links in the database itself.
The prepared database with pagerank is then taken by spdump.py to output the data within the 
database. The spjson is used to export the data from the database into a json file and then the 
force.html is used to visualize the web obtained, from the spider.js file.