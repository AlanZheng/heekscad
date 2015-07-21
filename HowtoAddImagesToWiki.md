## Introduction ##

This requires the ability to do svn commits. If you can edit pages here, you should be able to do that.


## Details ##

  1. Do **one** of the following:
    * Checkout the wiki from svn. From the command line, this is
      * `svn checkout https://heekscad.googlecode.com/svn/wiki HeeksCAD/wiki`
    * Checkout ALL of heekscad (not just the source). From the command line, this is
      * `svn checkout https://heekscad.googlecode.com/svn HeeksCAD`
  1. Put your image in the folder HeeksCAD/wiki/images
  1. Add it to svn, using `svn add <filename>`
  1. Change its mime-type so that it will show up. For a PNG image:
    * `svn propset svn:mime-type image/png myimage.png`
  1. Link to your image from a wiki page - use this url:
    * _http://heekscad.googlecode.com/svn/wiki/images/myimage.png_
