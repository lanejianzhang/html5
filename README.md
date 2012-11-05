You should debug as server start like: http://localhost:4567/rotate_image.html

You should not debug as file:///home.../rotate_image.html because SECURITY_ERR.

This example I use sinatra and thin as web server. How to use sinatra see : http://www.sinatrarb.com/intro

$gem install sinatra

$gem install thin

Start server:

$ruby -rubygems index.rb

Go: http://localhost:4567/rotate_image.html


All files are in folder "/public". Features list:

freehand_draw.html -- Draw something on an canvas. You can change the ocpacity, color, size of the brush.

rotate_image.html -- Rotate an image by clicking and dragmoving a point on the image.