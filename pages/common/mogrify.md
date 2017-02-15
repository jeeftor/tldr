# mogrify

> Perform various graphical operations on an image file.  
> By default this command will overwrite the image.
> Part of ImageMagick Library.


- Resize an image file to 50% of its original size:

`mogrify -resize 50% {{filename}}`

- Convert all png files to jpg:

`mogrify -format {{jpg}} {{*.png}}`

-

``