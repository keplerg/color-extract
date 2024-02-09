# color-extract

The Image Color Extract PHP class pulls the most common colors out of an image file. The color values are in hexidecimal. You can try it out below. Upload a file or use the sample image provided. This class was originally written by Csongor Zalatnai. You can get his original version here: https://www.phpclasses.org/browse/package/3370.html.

I added added some enhancements to this class:

- Allow you to select the quantization delta. The smaller the delta the more accurate the color. This also increases the number of similar colors though.
- Added a filter to reduce brightness variants of the same color.
- Added a filter to reduce gradient variants ( useful for logos ).
- Changed color counts to percentages.

You can try the online demo here: https://coolphptools.com/color_extract
