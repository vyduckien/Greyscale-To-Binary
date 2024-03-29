# 8-bit Greyscale To Binary Color

This is a class project for the course ECE 220 (EE2415: Computer System and Programming Languages - HCMUT). Feel free to share and distribute the code.

## Introduction

This program converts an greyscale BMP file of 8-bit color depth to a binary bmp file.

The color of the original image is not simply changed, but __*also the header information is also modified*__.

The resultant image contain the new header file corresponding to the dimension and its color depth, as well as reduced size due to compression.

Due to the fact that in 1-bit color BMP file there is only one 1 bit for a pixel instead of 8 bits in the case of an 8-bit BMP file, the file size should theoretically be reduced by **1/8**.

In order for the program to work, the original image file **MUST** have a color depth of 8 bits, and should contain an approriate color table.

The program lets user choose between dithering and no-dithering mode.

**Note**: Dithering mode is still not perfect due to some uknown miscalculation.

## Demonstration

Original (257 KB):

![Origin](https://i.imgur.com/BQNXv8T.png)

Result (32 KB, without dithering):

![Result](https://i.imgur.com/CNEQaTm.png)

Result (32 KB, with dithering):

![Result](https://i.imgur.com/JAzpuxu.png)

## Reference 

BMP file format:

https://en.wikipedia.org/wiki/BMP_file_format

http://www.ece.ualberta.ca/~elliott/ee552/studentAppNotes/2003_w/misc/bmp_file_format/bmp_file_format.htm 

[BMP Suite Image List](http://entropymine.com/jason/bmpsuite/bmpsuite/html/bmpsuite.html)
