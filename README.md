# Welcome to the repository of the program

This is the program that converts an greyscale BMP file of 8-bit color depth to a binary bmp file.

This program does not simply change the color of the original image, but *also modifies the header information*.

The resultant image has the relevant value, as well as reduced size due to compression.

Due to the fact that in 1-bit color BMP file there is only one 1 bit for a pixel instead of 8 bits in the case of an 8-bit BMP file, the file size should theoretically be reduced by 1/8.
