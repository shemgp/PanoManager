# PanoManager - Panorama Manager

This is a tool, built with QT that is used to manage panorama tours.
It loads equirectangular images, creates cube faces (which can then be annotated), and allows the interactive generation of tours.

## Overview

A Tour contains:
* Scenes - A scene contains six cube-face images, and a number of nodes.
* Nodes - These can be links to other scenes, information points, or links to media files.

A tour is saved in a 'pmp' file.  Once complete, the tour can be exported to a folder, where the appropriate web files are created.

Tours can currently be created for 'Pannellum' and 'Marzipano', and a snapshot of the Pannellum and Marzipano built files are included (with links to get the latest versions directly).

## Licencing

The following Licences apply:

* PanoManager: GPL
* QT: GPL / LGPL
* Pannellum: MIT
* Marzipano: Apache

## Limitations and Caveats

The PanoManager program is provided without warranty.  I am not a software engineer, and don't provide any warranty as to the quality, performance or maintainability of this code.  Please feel free to copy and expand the program, but ensure that all authors are appropriately recognised.

## Author

PanoManager - Steve Clarke