Using Tile Map Service component
================================

To add raster components to a dashboard, we can use tile map services instead of having to cre-ate charts before. Let’s take an example.

Create a new dashboard. You can select the « Two Heroes » template.  An empty dashboard is create. Drag a « Tile Map Service » component to an empty cell on the dashboard.

.. image:: ../images/dashboard/tile_map_service_1.png
    :align: center

You have added an empty tile map service component to the dashboard.

.. image:: ../images/dashboard/tile_map_service_2.png
    :align: center

We can get the details of a tile map service from an external system, e.g., by accessing Tile Detail of EOFactory’s images (please read Section 4.1.5 for more information).

.. image:: ../images/dashboard/tile_map_service_3.png
    :align: center

Copy the value of the Tile url, Min zoom, Max zoom and BBox fields from EOFactory and paste them to the corresponding fields on the dashboard.

.. image:: ../images/dashboard/tile_map_service_4.png
    :align: center

Next, we can drag an Overlay component to the other cell of the dashboard. Then, drag an Open Street Map component and Tile Map Service component on the Overlay. Fill in the new tile map service component the same values as the previous.

.. image:: ../images/dashboard/tile_map_service_5.png
    :align: center

Run the dashboard, then we get the dashboard with the tile map components on it.

.. image:: ../images/dashboard/tile_map_service_6.png
    :align: center