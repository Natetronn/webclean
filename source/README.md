## Png to Bitmap Conversion

Image Dimensions: 640x480 

Image Size: 900.1 KiB (921,654)

**Windows:**

Microsoft Paint's Save As 24-bit bitmap (bmp) 

**Linux:**

First use Trimage Image Compressor, or similar, on the PNG. Then convert to BMP using the following:

imagemagick cmd: 

`convert -quality 100 [image-path].jpg [image-path].bmp`


Note: anything larger than around 921KiB for the background image doesn't seem to work. 1.3MB image didn't work, anyway. I tried using an svg as well, as it was only 22k, for kicks and giggles to see what would happen but, that didn't work, of course. Must be a .bmp filetype, it seems. If anyone knows how to edit the bios to accept other filetypes let me know.


