chartscape
==========

Inkscape extension to create charts. For the time being, it's possible to create just pie charts.
This extension is written in Python. You'll need a Python interpreter in order to use it.
This code was written 4 years ago and I was a young developer on that time, so, sorry for ugly code or bugs.

Install
=======

Copy files chartscape.inx and chartscape.py to your Inkscape extensions directory.

Usage
=====

Open Inkscape (reopen it if it was already opened before installing the extension) and click on Extensions > Render > Chartscape.

Choose a title, the values for the pie chart (separated by commas), and the diameter. Click 'OK'.

A whole chart will be rendered, grouped. You can ungroup and edit each part of the chart separately.

To Do
=====

* Ideally, a refactoring, even to make the code more beautiful
* Legend box width (not perfect yet)
* Choose color palette (hardcoded to blue variations now)
* Simplify setAttribute calls
* Modularization
* Add new charts (line, bars, etc.)
* Add more options (color palette, chart type, show legend, etc.)
* Review code comments
* Adjust percentages positions

Thanks
======

Thanks to my friends:

* Leandro Andrade, for correcting the percentages positions
* Melissa Wen, for general improvements
* Aurélio Heckert, which presented to me the awesome world of Inkscape extensions development
