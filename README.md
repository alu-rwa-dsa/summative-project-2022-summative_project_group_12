[[Xplore Kigali](https://colab.research.google.com/drive/18xsrTk5O9am9WtcNJCR2TFv49ReF4BkG#scrollTo=view-in-github)] <--Link to the **Google collab**

### NB: Make sure to download the file first to access the link to our video.



# Xplore Kigali
Shortest path calculation and route plotting in Kigali, in interactive Folium map, based on Dijkstra's pathfinding algorithm.

--> The type of project we have workend on for this assignment is to create our own smaller and simpler version of mapping platform like Google maps, which is targeted for international students (even locals) in Kigali (primarily at ALU) to help them navigate the short pathes from source/starting point to their desired destination.

--> We worked on this program using Google collab since there were some dependencies (modules/libraries) that were not supported on pycharm, so we have found it to be more effective to work on Google collab.

### -->Those dependencies that are required for this program to run:
    import numpy as np
    import math
    import folium
    import contextily as ctx
    import shapely
    import osmnx as ox
    import geopandas as gpd
    from pyproj import Transformer
    from shapely.geometry import  Point, Polygon, LineString
    from matplotlib.ticker import FormatStrFormatter
    from matplotlib.patches import Circle
    from osgeo import ogr
    import matplotlib.pyplot as plt
    %matplotlib inline
    
NB: The main dependencies to run this program are ***contextily and osmnx*** which have to be downloaded first.

### --> They can be download using the following commands:
      pip install osmnx==0.16.2
      pip install contextily 
      
---> This a simple and fun to use program that uses various utilities and creates something useful in which people(students) can actually benefit from and we are actually solving a real life problem (Problems that we, ourselves have faced). It has a lot of potential and can actually be deployed as a web app.( We tried to deploy it using anvil and almost finished everything up but unfortunately anvil doesnt support folium (which is the responsible package to display the map) and we were not able to do so.)

-->The video we have submiited is about **17min** and the reason for that is that we had to explain about **the functionalities and dependencies** of our program. 

--> If there are any questions or concerns, please feel free to get in touch with us. Cheers!

### Contributers:
      --> Abraham Diress (Cohort 3)
      --> Henos Tadesse (Cohort 2)
      --> David Soro (Cohort 2)
      
@summative_project_group_12

### Further Requirements details
<pre>
numpy == 1.19.5                     contextily == 1.1.0               osgeo == 2.2.3
matplotlib == 3.4.3                 shapely == 1.7.1                  pyproj == 3.2.0
folium == 0.8.3                     osmnx == 0.16.2                   geopandas == 0.9.0 
</pre>
