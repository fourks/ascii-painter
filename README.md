# ascii-painter
Ascii-painter is a toolkit (released under the MIT license) that allows you to make roguelike maps out of ascii tiles. 

Ascii-painter grew out of a roguelike game I'm writing. I needed a way to easily hand-place tiles in certain maps.
In ascii-painter, you can use random map generators to fill out most of the map, then using the brush tools, specially
place tiles in the exact area you need them.

This tool would be good for creating static city/town levels for instance.

Binaries
--------
Windows & OS X binaries are in the [releases](https://github.com/eu90h/ascii-painter/releases) section.

Screenshots
-----------
Some ascii folk singing a tune near a bonfire

![Bonfire](https://i.imgur.com/FOaNcTi.png)

An old example

![Example Map](https://i.imgur.com/U4cHvWG.png)

A World Map

![World Map](https://i.imgur.com/NunOIhN.png)

Picking a color:

![Color Picker](https://i.imgur.com/yjOMfiE.png)

Finally, no Lisp program is complete without Lambdas!

![Lambda](https://i.imgur.com/DG5qYXV.png)

Usage
-----
The default map is 100x60. To change the dimensions, click File->New Map.

The camera is controlled with the arrow keys. Undo is `ctrl-z`, and `ctrl-s` saves the current tile to the tile library.

Features
--------
* Brushes (Paintbrush, single painter, shape brush)
* Generators (Fill map, Random Placement)
* Full color support
* All glyphs in code-page 437 supported
* Saving and loading maps in csv format
* Undo (press ctrl-z)

Upcoming Features
-----------------
* More random map generators

Credits
-------
* Thanks to @jpverkamp for ascii-canvas
