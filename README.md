OwnCloud Bootswatch Themes
==========================

This is a collection of free themes for [Owncloud](http://owncloud.org/), based on [Bootswatch](http://bootswatch.com), which is based
on [Bootstrap](http://getbootstrap.com/).

Usage
-----

Clone or download the repository, copy one of the themes to `owncloud/themes` directory, and then
add `"theme" => "bootstrap_theme"` to `owncloud/config/config.php`.

Head over to [Bootswatch](http://bootswatch.com) and take a look on the available themes.

Customization
-------------

Just like Bootswatch, OwnCloud Bootswatch can be customized.

Check out the [Help page](http://bootswatch.com/help/) for more details on building your own theme.

Like Bootswatch, OwnCloud Bootswatch uses Grunt and NodeJS for building LESS files.

Working on top of Bootswatch pattersns, the main file is `global/owncloud.less`, that uses
Bootstrap `variables.less` file (and, of course, bootswatch `variable.less` of each theme) to get
the colors from bootsrap and make some little adjustments.

Author
------

[Rafael Goulart](http://github.com/rafaelgou)

Copyright and License
---------------------

Copyright 2014 Rafael Goulart
Bootstwatch Copyright 2013 Thomas Park

Code released under the MIT License.
