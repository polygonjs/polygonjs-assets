# script to create a thumbnails for exr files:

`mogrify -resize 128x128 -format jpg -quality 80 -path ./thumbnails *.exr`