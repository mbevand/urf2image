This is a fork of https://github.com/superna9999/urf_work with my own improvements (bugfixes.)

These tools convert a URF file (the Apple raster format used for AirPrint, aka UNIRAST, aka image/urf) to BMP format.

urftobmp.c decodes the data to one bmp file per page. It does not handle the Colorspace/Duplex Mode/Quality or Dots per Inches informations.

superna9999 initially wrote these tools based on reversed engineered information provided at https://github.com/AlanQuatermain/unirast
