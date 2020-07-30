# AleksPetrakov/svg-sprite
This is a fork of [svg-sprite](https://github.com/jkphl/svg-sprite) with some modifications. Remove PhantomJS which is very large for main project. 

## Modifications

lib/svg-sprite/shape.js

  * delete PhantomJs process when there are no width and height

# svg-sprite

is a low-level [Node.js](http://nodejs.org/) module that **takes a bunch of [SVG](http://www.w3.org/TR/SVG/) files**, optimizes them and bakes them into **SVG sprites** of several types.
