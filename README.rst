cmsplugin-socialbuttons
=======================

A simple plugin for adding social buttons.

Default icons by Paul Robert Lloyd
(http://paulrobertlloyd.com/2009/06/social_media_icons)

Or you can use Font Awesome instead
(http://fontawesome.io/)


Supported buttons
-----------------

At the moment, following buttons are available:

  * Facebook
  * Twitter
  * YouTube
  * Google+
  * RSS
  * Foursquare
  * GitHub
  * Instagram
  * Flickr

Feel free and fork this, so that you can add your required button. Don't forget
to push your changeset!


Installation
------------

Using pip you can simply type into a terminal:

  pip install cmsplugin-socialbuttons


Configuration
-------------

Add ``cmsplugin_socialbuttons`` to the list of ``INSTALLED_APPS`` in your
``settings.py`` file.

Run migrations ``python manage.py migrate cmsplugin_socialbuttons``


Please make sure, that jQuery is provided!


Icons
-----

Icons from http://icondock.com/free/vector-social-media-icons and Font Awesome http://fontawesome.io/


LICENSE
-------

Released under the BSD license.
