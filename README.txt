Emogrifier

   This module uses the [1]emogrifier class library as an input filter to
   convert stylesheet rules to inline style attributes. This ensures
   proper display on email and mobile device readers that lack stylesheet
   support.

Installation

    1. Ensure that the PHP [2]Document Object Model extension is
       available. Emogrifier requires the dom extension and will not work
       without it.
    2. Download, install, and enable the [3]Libraries module.
    3. Create a library directory for the Emogrifier library in one of the
       following locations:
          + sites/all/libraries/emogrifier (recommended)
          + sites/DOMAIN/libraries/emogrifier
          + profiles/PROFILE/libraries/emogrifier
       DOMAIN is your website domain name, and PROFILE is the installation
       profile you selected when installing Drupal.
    4. [4]Download the emogrifier.php and place it within the library
       directory you just created.
    5. [5]Install [6]this module and enable it.
    6. Visit admin/configure/content/formats or click on

     Administer >> Configuration >> Content authoring >> Text formats
       to set up a new input format or add Emogrifier filtering to an
       existing format.

References

   1. http://www.pelagosdesign.com/sidecar/emogrifier/
   2. http://php.net/dom
   3. http://drupal.org/project/libraries
   4. http://www.pelagodesign.com/sidecar/emogrifier/
   5. http://drupal.org/node/895232
   6. http://drupal.org/project/emogrifier
