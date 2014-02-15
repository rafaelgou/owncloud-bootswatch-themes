OwnCloud Bootswatch Themes
==========================

This is a collection of free themes for [Owncloud](http://owncloud.org/), based on [Bootswatch](http://bootswatch.com), which is based
on [Bootstrap](http://getbootstrap.com/).

Usage
-----

Clone or download the repository, copy one of the themes to `owncloud/themes` directory, and then
add `"theme" => "bootstrap_theme"` to `owncloud/config/config.php`.

Head over to [Bootswatch](http://bootswatch.com) and take a look on the available themes.

You have the default Bootstrap theme also in this package.

Customization
-------------

Just like Bootswatch, OwnCloud Bootswatch can be customized.

Like Bootswatch, OwnCloud Bootswatch uses Grunt and NodeJS for building LESS files.

Working on top of Bootswatch patterns, the main file `global/owncloud.less` uses
Bootstrap `variables.less` file (and, of course, bootswatch `variable.less` of each theme) to get
the colors from Bootstrap and make some little adjustments.

To modify a theme or create your own, follow the steps below in your terminal. You'll need to have Git and Node installed.

    git clone https://github.com/rafaelgou/owncloud-bootswatch-themes
    npm install
    git submodule init
    git submodule update

Edit owncloud.less in one of the theme directories, or create your own in /custom 
(please be aware that `global/owncloud` is not a theme itself, but used to build all themes - 
change it only if you want to change anything globaly).

Type grunt swatch:[theme] to build the CSS for a theme, e.g., grunt swatch:amelia for Amelia. Or type grunt swatch to build them all at once. To have grunt available in the command line, install grunt-cli as described on the [Grunt Getting Started page](http://gruntjs.com/getting-started).


Author
------

[Rafael Goulart](http://github.com/rafaelgou)

Copyright and License
---------------------

Copyright 2014 Rafael Goulart
Bootstwatch Copyright 2013 Thomas Park

Code released under the MIT License.
