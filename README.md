<h1>About Invisimail for BackdropCMS</h1>
-------------------------

This module is a port to Backdrop of the Drupal contributed module 'Invisimail'. 
Invisimail provides a content filter to hide email addresses from spam-bots. 
Email addresses are converted to ascii code and optionally written to the page 
using a concatenated JavaScript "write" command. 

The email addresses will appear on the page normally, but their html source 
will be obscured so as not to appear as an email address to email harvesting robots. 
Invisimail also provides an option to automatically create mailto links 
for email addresses.


<h2>Status</h2>

This port to Backdrop is ready for installation and testing but is not yet proven reliable.

<h2>Installation</h2>

Install this module in the usual way.
You will then find two more filter option in Text Formats.

1. Encode email addresses: HTML entities 
2. Encode email addresses: Javascript-wrapped HTML entities 

Note that you may need to set the invisimail filter to apply after any modules 
that modify HTML, such as HTML Filter, depending on the settings you select for each.

<h2>License</h2>

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
    
    
<h2>Maintainers</h2>

<h3>For Drupal:</h3>

Larry Garfield (Crell); Jeff Robbins (jjeff)



<h3>Port to Backdrop:</h3>
Graham Oliver github.com/Graham-72

<h3>Acknowledgement</h3>

This port to Backdrop would not, of course, be possible without all the work done by the developers 
and maintainers of the Drupal module.
