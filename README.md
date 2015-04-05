Responsify Images
=======================

This is a quick and lazy tool to quickly scale your images to various different size.

This is my lazy implementation of [grunt-responsive-images](https://github.com/andismith/grunt-responsive-images/) for my own quick and dirty tools to scale images. Big credit to [Andi Smith](https://github.com/andismith) for sharing this.

By default this will scale your images into small, medium, and large. for further setting configuration of this, refer to Grunfile.js

Requirement to run this tool:
-----------------------------------

* [Node JS](https://nodejs.org/)
* [Grunt-CLI](http://gruntjs.com/getting-started)
* [Graphics Magick](http://www.graphicsmagick.org/index.html) or [Image Magick](http://www.imagemagick.org/)


To use this tool to scale the images:
-------------------------------------

* put folder of images inside 'src' folder.
* run ```grunt```
* Voila! the scaled images are now inside the 'dist' folder

This tool is built based on the following guide and technology:
----------------------------------------------------------

* [Generate multi-resolution images for srcset with Grunt](http://addyosmani.com/blog/generate-multi-resolution-images-for-srcset-with-grunt/)
* [Grunt Responsive Images](http://www.andismith.com/grunt-responsive-images/)

Further README and credit of this technology:
------------------------------------------

#[grunt-responsive-images](https://github.com/andismith/grunt-responsive-images/)

Big credit to [Andi Smith](https://github.com/andismith), and if you like to support or contribute more to this. please checkout the [source github](https://github.com/andismith/grunt-responsive-images/)
