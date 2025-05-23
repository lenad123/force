.. _aux-level:

Auxiliary
=========

**Table 1.** Components.

+--------+------------------------+-------+---------------------------------------------------------+
| Module | Program                | Level | Short description                                       |
+========+========================+=======+=========================================================+
| AUX    | force                  | /     | Print version, short disclaimer, available modules etc. |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-parameter        | /     | Generation of parameter files                           |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-train            | /     | Training (and validation) of Machine Learning models    |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-qai-inflate      | /     | Inflate QAI bit layers                                  |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-tile-finder      | /     | Find the tile, pixel, and chunk of a given coordinate   |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-tile-extent      | /     | Create a tile allow-list from aoi (vector file)         |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-tabulate-grid    | /     | Extract the processing grid as shapefile                |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-cube             | /     | Ingestion of auxiliary data into datacube format        |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-cube-init        | /     | Generation of datacube from certain projection          |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-procmask         | /     | Generate a processing mask from continuous data         |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-pyramid          | /     | Generation of image pyramids                            |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-mosaic           | /     | Mosaicking of image chips                               |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-synthmix         | /     | Synthetic mixing of training data                       |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-stack            |       | Stack images, works with 4D data model                  |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-mdcp             |       | Copy FORCE metadata from one file to another            |
+--------+------------------------+-------+---------------------------------------------------------+
|        | force-magic-parameters |       | Generate parameterfiles from replacement values         |
+--------+------------------------+-------+---------------------------------------------------------+




The FORCE Auxiliary Functionality (FORCE AUX) component is intended to provide small helper programs for specific purposes, e.g. the location of coordinates.



A glimpse of what you get:

.. figure:: ../../howto/img/tutorial-datacube-google-grid.jpg
   
   *ARD processing grid. 
   This figure shows a Google Earth screenshot with ARD grid overlay. The grid cells are 30 x 30km in EPSG:3035. 
   [The grid was generated using force-tabulate-grid]*


.. toctree::
   :maxdepth: 2

   main.rst
   parameter.rst
   train.rst
   qai-inflate.rst
   tile-finder.rst
   tile-extent.rst   
   tabulate-grid.rst
   cube.rst
   cube-init.rst
   procmask.rst
   pyramid.rst
   mosaic.rst
   synthmix.rst
   stack.rst
   mdcp.rst   
   magic-parameters.rst
