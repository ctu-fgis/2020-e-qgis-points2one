.. Point2One documentation master file, created by
   sphinx-quickstart on Sun Feb 12 17:11:03 2012.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Points2One's tutorial
============================================

How it works:

In the Input vector layer section there is a combo box where you can choose which layer you want to use.  

Under the combo box there are 3 checkboxes:

* Create polygon - create a polygon layer 

* Create lines - create a linestring layer

* Closed - the last point be connected to first one, completing the circuit

You can chosse some parameters to connect the points. By default, the points are connected in the order they are in the selected point layer.

If you check 

* Sort vertices by - select an attribute, the order of connecting points will change from the lowest to the highest number in selected attribute or alphabetically from A-Z if the attribute is a string


* Group features by - it divide the selected point layer into groups that have the same value in the attribute selected in the combo box

The last feature of this module is saving output geopackage, where you type in the name of the newly created layer and path to where it should be saved. By pressing OK it will create a geopackage that includes all informations about the newly created layer. There is a limitation to that: if you already have a geopackage with that name saved and you want to create a different layer with the same name, the new layer will not be created, so there are 2 choices, either you change the filename or you will have to delete the geopackage with the name you want to use first. If output geopackage is not checked however, the new layer will still be created, but saved only as an in-memory layer therefore you will lose the data after you close the project.


You can watch `Video tutorial
<video/points2one.mp4>`__


Content
---------------------
`Introduction
<index.html>`__

`Installation
<installation.html>`__



