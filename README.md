


# Desaturating images

All images in the website must be desaturated. In order to achieve this, install ImageMagick:

´´´
sudo apt install imagemagick
´´´

Then desaturate the image with this command:

´´´
convert input.jpg -modulate 100,50,100 output.jpg
´´´
