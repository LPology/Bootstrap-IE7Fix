Bootstrap 3 IE7 Fix
============================
Adds IE7 support to Bootstrap 3.

### How to Use ###
Add this conditional after bootstrap.css:

```html
<!--[if lt IE 8]>
    <link href="/css/bootstrap-ie7fix.css" rel="stylesheet">
<![endif]-->
```

If you aren't currently using <a href="https://github.com/scottjehl/Respond">Respond.js</a>, you'll need to add it in order to support media queries.

Special thanks to <a href="https://github.com/coliff">coliff</a> for a starting point, and <a href="https://github.com/rassie">rassie</a> for the Glyphicon code.

### About ###
* Adds IE7-specific formatting to Bootstrap components and HTML elements
* Fixes IE hasLayout bug with zoom
* Applies IE inline hack to fix the inline-block bug
* Uses Bootstrap 2.x grid layout, so no box-sizing polyfill is required
* VM tested for most reliability

### Notes ###


### License ###
Released under the MIT license.