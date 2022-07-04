# bmp

A library for loading and storing BMP files.

## Usage

The library provides a single record type `bmp`.

	make-bmp
	bmp?
	bmp-height
	bmp-width
	bmp-bytevector

The record contains the values for the width and height of an image and, a bytevector of pixel data stored in BGRA8888 format.

    read
    write

These procedures construct and write a `bmp` record to a binary port.
