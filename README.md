Bootstrap 3 IE7 Fix
============================
Adds IE7 support to Bootstrap 3.

### How to Use ###
Add this conditional after bootstrap.css:

```html
<!--[if lt IE 8]>
    <link href="css/bootstrap-ie7fix.css" rel="stylesheet">
<![endif]-->
```

If you're not already using <a href="https://github.com/scottjehl/Respond">Respond.js</a>, you'll need to add it to support media queries.

### About ###
* Adds IE7-specific formatting to Bootstrap components and HTML elements
* Fixes IE hasLayout bug with zoom
* Applies IE inline hack to fix the inline-block bug
* VM tested for most reliability

### Notes ###
* Most of the core components of Bootstrap have been tested -- grid system, buttons, forms, tables, etc., but there is more to work on. 
* To avoid the need for a box-sizing polyphill, the grid system is overriden with the Bootstrap 2.x grid layout.
* Microsoft provides free VMs (<a href="http://www.modern.ie/en-us/virtualization-tools#downloads">here</a>) for testing in older versions of IE. This is far more accurate than the version emulator in IE.

Special thanks to <a href="https://github.com/coliff">coliff</a> for a starting point, and <a href="https://github.com/rassie">rassie</a> for the Glyphicon code.

### License ###
Released under the MIT license.