
Media: TagTélé

This adds support for the French TagTélé video sharing service, available at
http://www.tagtele.com/

To use this module, you'll first need to install Embedded Video Field, which is
packaged with Embedded Media Field (from http://drupal.org/project/emfield).

Set up a content type to use a Third Party Video field as you normally would 
with emfield. Also ensure that you have enabled the new TagTélé provider from 
the Admin screen at /admin/content/emfield.

AUTOPLAY
--------
To force autoplay, add a “/1” at the end of the URL that you paste or modify 
the embed code to add the “/1” to the end of url in object param “value” and 
“embed” src attributes.
