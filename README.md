# [Emogrifier](http://drupal.org/project/emogrifier)

Uses the [emogrifier library](https://github.com/jjriv/emogrifier) to modify
CSS in HTML emails.

Some mail clinets (like Gmail) filters out CSS style definitions from the HTML.
To work around this problem, Emogrifier converts all CSS styles to inline
CSS.

### [Installation](http://drupal.org/documentation/install/modules-themes/modules-7)

1.  The module depends on the Emogrifier library (pelago/emogrifier). The easiest way
    to handle this is by [using composer](https://www.drupal.org/node/2404989).

2.  Enable the module.

### Development version

The module has only been tested with Simplenews in combination with Swiftmailer.

We need to improve the module by making it compatible with other modules and by
providing automated tests.
