Invisimail
==========

This module is a port to Backdrop of the Drupal contributed module 'Invisimail'.
Invisimail provides a content filter to hide email addresses from spam-bots.
Email addresses are converted to ascii code and optionally written to the page
using a concatenated JavaScript "write" command.

The email addresses will appear on the page normally, but their html source will
be obscured so as not to appear as an email address to email harvesting robots.
Invisimail also provides an option to automatically create mailto links for
email addresses.

Status
------

This port to Backdrop is ready for installation and testing but is not yet
proven reliable.

Installation
------------

Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules.
You will then find two more filter options in Text Formats.

1. Encode email addresses: HTML entities
2. Encode email addresses: Javascript-wrapped HTML entities

Note that you will need to set the Invisimail filter to apply after any other
filters that modify HTML, such as 'Limit allowed HTML tags' and 'Correct faulty
and chopped off HTML'. If in doubt, put the Invisimail filter last.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Maintainers
-----------

### For Drupal:

Larry Garfield (Crell)
Jeff Robbins (jjeff)

### Port to Backdrop:

Graham Oliver (github.com/Graham-72)

Acknowledgement
---------------

This port to Backdrop would not, of course, be possible without all the work
done by the developers and maintainers of the Drupal module.

