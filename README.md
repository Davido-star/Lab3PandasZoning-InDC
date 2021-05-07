# Lab3 David Smtith   
From using pandas to publishing a web map using CARTO! WHOOTWHOOT   
Housing in any major city is an issue, but DC is unique. DC is the nation’s capital and should set an example for the rest of the county. The city of DC is trying something out called “Planned Units of Development” (PUD’s) to curb the adverse effects of gentrification while harnessing some of the economic benefits. In this tutorial, PUD zoning in DC is explored using free and open zoning data from OpenData.dc.gov. – a government-hosted data portal that is cool. We took the PUD data from the website and used python to merge datasets to create a new one that can be visualized. The initial requirement to do this was to get the python tool dependencies in order. We imported GeoPandas (data management and visual tool), Shapely (a GIS package that works with GeoPandas), and rtree to get things going. From here, the data we needed was accessed through google drive. This step was highly beneficial to practice again. Importing files to colab has many capabilities and implications for my personal goal to a universal cloud computing future with python. With three lines of code, my drive was linked, and I was ready to start defining variables that would hose my data from the drive -seem less. I ran into an issue with importing my files to colab but solved it by cross-referencing the file names used between my folders and the tutorial. The final output was a geodata frame containing zoning attributes and polygon locations of PUD in DC. The new shapefile was saved to my google drive, and I visualized it in CARTO. CARTO is a beautiful interface that allows for easy web mapping and internet publication; check out my final map here https://davido-star.carto.com/builder/18acf4e4-af05-468b-aa64-176e9289ad28/embed .   

![image](https://user-images.githubusercontent.com/73979215/117487800-8e47d100-af39-11eb-9781-9c28c3c51151.png)    
Figure 1: Finial output from tutorial in greyscale. 
