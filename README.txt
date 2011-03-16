Emogrifier
----------

This module uses the emogrifier class library [1] as an input filter to convert
stylesheet rules to inline style attributes. This ensures proper display on
email and mobile device readers that lack stylesheet support.

Installation
------------

1. Ensure that the PHP Document Object Model (dom) extension [2] is available.
   Emogrifier requires the dom extension and will not work without it.

2. Download, install, and enable the libraries module [3][4].

3. Create a library directory for the Emogrifier library in one of the
   following locations:

   * sites/all/libraries/emogrifier
   * sites/DOMAIN/libraries/emogrifier
   * profiles/PROFILE/libraries/emogrifier

   DOMAIN is your website domain name, and PROFILE is the installation
   profile you selected when installing Drupal.

4. Download the emogrifier.php file [1] and place it within the library
   directory you just created.

5. Install this module and enable it. [4][5]

6. Visit admin/configure/content/formats or click on

     Administer >> Configuration >> Content authoring >> Text formats

   to set up a new input format or add Emogrifier filtering to an existing
   format.

--------------------------------------------------------------------------------

[1]  http://www.pelagodesign.com/sidecar/emogrifier/
[2]  http://php.net/dom
[3]  http://drupal.org/project/libraries
[4]  http://drupal.org/node/895232
[5]  http://drupal.org/project/emogrifier
