# This is an example filestructure and filecontents of a Docker Container
This uses Nodemon for hot reloading, and also uses Handebars to manage parameters that can be set in ```server.js```. 
Handlebars uses index.html as the main template, and uses the example further webpages ```e1.html``` and ```e2.hmtl``` as extra templates.

> NOTE: If you want to use this in development mode, you have to set the ```NODE_ENV``` variable in your ```zshrc``` file to ```development```, as it defaults to production causing it to not use Nodemon.
