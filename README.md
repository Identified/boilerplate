# Description #
This is a quick starter for bootstrapping a static web project with using Slim, Coffeescript, SASS, and HTML5.

## How to Use ##
All SASS related files are in the /sass folder.
Everything should be ready to go, if you do this stuff -- and have rails and node on your machine.

From the command-line: 
    
    bower install
    gem install compass
    
From your 'puter:

Install http://livereload.com/ and add this project (or a copy of it) so that your slim, coffeescript, and sass files are updated.
Be sure that LiveReload doesn't try to do anything with the stuff in bower_components folder.


### CSS Files ###
The main CSS file, style.css, is compiled from sass/application.scss which imports all your other stylesheets. Use the theme folder for global stuff and the views folder for very specific CSS changes relating to pages/partials.

### Coffee/Javascript Files ###
Modernizer is included. You man want to trim things down with a custom version here: http://modernizr.com/


## Documentation for Libraries ##
* <a href="http://html5boilerplate.com/">HTML5 Boilerplate</a>
* <a href="http://sass-lang.com/">SASS</a>
* <a href="http://necolas.github.com/normalize.css/">normalize.css</a>
* <a href="http://livereload.com/">Live Reload</a>
* <a href="* <a href="http://bower.io">Bower</a>
* <a href="* <a href="http://slim-lang.com/">Slim</a>
* <a href="* <a href="http://modernizr.com/">Modernizr</a>

