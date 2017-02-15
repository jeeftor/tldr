# display

> Display an image or sequences of images on any X Server.
> Part of ImageMagick Library.

- Display an image:

`display {{filename}}`

- Tile a texture onto the root window of x server:

`display -size 1280x1024 -window root {{slate.png}}`

- To display a visual image directory of all your JPEG images, use:

`display 'vid:*.jpg'`

