# Sand Table File Preview - Polar Plot

I wanted a way to view .thr files that are used for kinetic art sand tables, I knew it could probably be done in JS but couldn't find anything.

This is a standalone one that simply runs in the browser, entirely client side.

https://polarplot.github.io/

The .thr [file format can be seen on the Dune Weaver GitHub page](https://github.com/tuanchris/dune-weaver/tree/main?tab=readme-ov-file#pattern-file-format) but basically it's the [Polar coordinate system](https://en.wikipedia.org/wiki/Polar_coordinate_system).

.txt files in the same format are also supported.

Note: This only works with tables that take polar coordinates as input, Gcode files are not supported, there is already Gcode viewers out there.

Technically you can import .thr files into [Sandify](http://Sandify.org) as a layer but this is quicker and simpler.

## Credit

I was going to write it myself but it would've took me a while as I'm no JS expert but thankfully as part of the web interface for the [Dune Weaver](https://makerworld.com/en/models/841332#profileId-787553) sand table they had already made one, so the code is taken from [there](https://github.com/tuanchris/dune-weaver/blob/main/templates/index.html).
