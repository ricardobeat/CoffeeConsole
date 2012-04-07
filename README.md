A CoffeeScript tab for WebKits inspector.

In this fork:

* removed ACE and jQuery dependencies
* similar formatting to the standard console
* syntax checking for coffeescript (red = error)
* captures console output - only for code run from itself (will also make `console.*` return weird stuff)