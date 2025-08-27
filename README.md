# Cubic reasoning

This is my personal blog.

Some reminders to myself are below.

## Publishing

To publish, I need to run this command (from the ´master´ branch):

´´´
quarto publish gh-pages
´´´

# Desaturating images

All images in the website must be desaturated. In order to achieve this, I need to install ImageMagick:

´´´
sudo apt install imagemagick
´´´

Then desaturate the image with this command:

´´´
convert input.jpg -modulate 100,50,100 output.jpg
´´´
