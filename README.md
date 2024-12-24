# LSB-Image-Steganography
This C program implements a basic LSB (Least Significant Bit) image steganography technique. LSB steganography involves hiding information in the least significant bits of the pixel values in an image.

FEATURES
Embed text data into an image using LSB steganography.
Extract hidden text data from a steganographic image.
USAGE
Compilation
Compile the program using a C compiler. For example:

   1. gcc *.c
   2. ./a.out -e beautiful.bmp secret.txt stego.bmp  --> For Encoding
   3. ./a.out -d stego.bmp decode.txt  --> For Decoding
