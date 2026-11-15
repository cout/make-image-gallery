make-image-gallery
==================

A simple script to create an html page with thumbnails of and links to
images in a directory.

Usage:

    make-image-gallery <dir>

The script will:
* convert all png files to avif
* REMOVE the original png files
* create thumbnails of images in `<dir>/.thumbs`
* create `<dir>/index.html` with thumbnails and links to the converted
  images

Requirements:
* bash
* GNU make 4.x or newer
