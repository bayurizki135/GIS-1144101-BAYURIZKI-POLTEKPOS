BACKGROUND PROBLEM
In the previous article we have explained about the concept of geospatial data, but there has been no explanation about how to manufacture data QGIS application i.e. shp applications devoted to geographic information systems
Explanations and SOLUTIONS to PROBLEMS
For a discussion of this time we will learn how to create a geospatial data will then automatically be formed a file. These three files are: shp, shx and dbf.

Here's how the implementation of ataau way of making files shp
1. Originally first we open the command promt in Python by typing: Gis/Python
2. then type import shapefile. Writer (shapeType = 1) ENTER
3. type sf again. the point (10, 10, 0.0)
4. sf. field (' name ', ' C ', ' 40 ')
5. sf. record (' SLAVE ')
6. sf. save (' URbuat_file_geospasial.shp ')
7. exit ()

import shapefile is the default python library called shapefile.
-sf = shapefile. Writer (shapeType = 1) is to define the variable as a function of sf Writer that is creating the data file shp.
-sf. point (10, 10, 0, 0) is entering data point-shaped into the shp file we will create later.
-s.f. field (' name ', ' C ', ' 40 ') that defines the name of the table the following data type C that is Character and 40 defines its Lenght on the shp file data.
-sf. record (' Kusnadi ') that the contents of the table/field name that was created earlier
-sf. save (' URbuat_file_geospasial.shp ') was doing a save with the file name URbuat_file_geospasial.shp.


Conclusions and Suggestions
Create geospatial data is easy but need to understand how the processing of geospatial data based file shp can be used and utilized by many people.
The author's advice, learn how to create a file the following in order of processing and shp readers all could be more advanced and more adept at processing of geospatial data.
