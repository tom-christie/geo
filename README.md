geo
===

A javascript library for representing 2D shapes and their intersections.

## Organization

The library consists of two types of objects:

 - a global object that maintains the representation of the points/lines/circles, and
 - geometric objects themselves, including points, lines and circles.

 ## Geometric objects

Visible / invisible / partly visible (circles and lines)

Anchors - points/intersections/lines/circles that the user can INTERACT with, and by which other things are defined.  Things are anchors by default if they're explicitly created. Points / intersections that are "detected" are not anchors unless you tell them to be.