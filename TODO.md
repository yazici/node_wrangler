Todo
====

Short term:
-----------
* Add driver for mapping node (option for offset) - drive the position, rotation and scale with an Empty
* Color ramp element positions (node.color_ramp.elements[0])
* Clamp the output of selected nodes (Mix node, second input, Clamp on)
* Map Z-depth range by picking two points on the backdrop image (nearest, furthest), or by automatically mapping it so it's 0-1 (minimum 0, maximum 1)
* Comment node
 - Multiline
 - Automatic wordwrap
 - No character limit
 - Heading
 - Text colour
 - Use frame node and parent text to this
* Auto set frame range of image sequence
* Make sure everything works inside groups.
* Increase/Decrease mix fac hotkeys also work for other node values.
* Lazy functions should use the nearest border, not the nearest center
* Lazy Mix: when to/from node is the same node, add a clamp
* Nicer zooming of background image (Z to enter view transform mode, mouse wheel to zoom into cursor, backspace to reset) - just an idea

Long Term:
----------
* Tools for object/material index (both shading and compositing noodles, and for assigning)
* Node templates (store selection, new menu in Shift+A menu, new panel in toolbar) [Amaranth has one template, but only one, might like to look at this code]
* Better auto-arrange that uses the starting position of nodes and centers them nicely rather than a long row at the top and ugly vertical 'columns' - make interactive with circle around cursor - horizontal movement controls fac of arrangement, verticle controls spacing of nodes (or something).
* Set Camera clipping automatically (fire rays into scene progressively, show user real-time the min/max, have 'stop' button to cancel early and use those values, or stop after a certain number of rays). Also allow user to click the model in camera view to set closest/furthest. Include bgl visualisation of the progressive points, and bgl camera view borders (shown in non-camera persp)
