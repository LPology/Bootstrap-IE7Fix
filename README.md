Bootstrap 3 IE7 Fix
============================
Adds IE7 support to Bootstrap 3. 

* Applies IE7-specific styles to Bootstrap components and HTML elements
* Includes bug fixes for the usual suspects: hasLayout, inline-block bug, z-index bug., etc
* VM tested for greatest reliability

Demo: https://www.lpology.com

### How to Use ###
Add this conditional after bootstrap.css:

```html
<!--[if lt IE 8]>
  <link href="css/bootstrap-ie7fix.min.css" rel="stylesheet">
<![endif]-->
```

If you're not already using <a href="https://github.com/scottjehl/Respond">Respond.js</a>, you'll need to add it to support media queries. 

### Notes ###
* Tested with Bootstrap version 3.0.2
* Most of the core components of Bootstrap have been tested -- grid system, buttons, forms, tables, etc., but there is more to work on. 
* To avoid the need for a box-sizing polyfill, the grid system is overriden with the Bootstrap 2.3.2 grid layout.
* If you want to test or help improve, Microsoft provides free VMs (<a href="http://www.modern.ie/en-us/virtualization-tools#downloads">here</a>) for testing in older versions of IE. This is far more accurate than the version emulator in IE.

Special thanks to <a href="https://github.com/coliff">coliff</a> for a starting point, and <a href="https://github.com/rassie">rassie</a> for the Glyphicon code.

### License ###
Released under the Apache 2 license.