# wax

Tools for improving web maps. These are currently designed for [OpenLayers](http://openlayers.org/).

## Controls

* BlockSwitcher: a clone of [LayerSwitcher](http://dev.openlayers.org/docs/files/OpenLayers/Control/LayerSwitcher-js.html), with better themability and positioning.
* BlockToggle: a version of BlockSwitcher that toggles between two different layers only. Useful for situations in which layers represent the same data in slightly different ways.
* Legend: a block in a corner of a map that provides information on layers.
* Permalink: a version of [Permalink](http://dev.openlayers.org/docs/files/OpenLayers/Control/Permalink-js.html) optimized to persist layers between pages with different layer setups and without explicitly using the control.
* Popup: an interaction with point-based, clustered maps that allows clicking on points that results in scanning between items.
* Tooltip: an interaction with point-based maps that results in following links on hover.
* Scale Points: dynamic styling, changing point radii based on a certain value

## Notes

This module does not provide thorough theming or accessory images.

## Authors

- Tom MacWright (tmcw)
- Will White (willwhite)
