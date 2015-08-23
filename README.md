# BPG Arial

![Bower](https://img.shields.io/bower/v/bpg-arial.svg)
![Bower](https://img.shields.io/bower/l/bpg-arial.svg)
![Author](https://img.shields.io/badge/Font_Author-Besarion_Gugushvili-blue.svg)
![IE](https://img.shields.io/badge/IE_Support-6+-brightgreen.svg)
![Files](https://img.shields.io/badge/Font_Files-.ttf,_.eot,_.svg,_.woff,_.woff2-brightgreen.svg)

BPG Arial Web Font Package.

## Installation

Run the following command to install the font with [Bower](http://bower.io) (recommended):

```
$ bower install bpg-arial --save
```

Or install it manually, by [downloading the archive](https://github.com/web-fonts/bpg-arial/archive/master.zip) and placeing `/css/` and `/fonts/` directories to your project.

## Usage

BPG Arial web font package comes with 3 different css files:

* [bpg-arial.css](https://github.com/web-fonts/bpg-arial/tree/master/css/bpg-arial.css) - Modern way of including web fonts on web page, which contains only: `.woff` and `.woff2` files (see the browser support below).
* [bpg-arial.ie.css](https://github.com/web-fonts/bpg-arial/tree/master/css/bpg-arial.ie.css) - IE6-8, which contains: `.eot` font file only.
* [bpg-arial.legacy.css](https://github.com/web-fonts/bpg-arial/tree/master/css/bpg-arial.legacy.css) - [Bulletproof @font-face syntax](http://www.paulirish.com/2009/bulletproof-font-face-implementation-syntax/), which contains: `.eot`, `.ttf`, `.svg`, `.woff` and `.woff2` files.

### Modern Syntax (Recommended)

```html
<link rel="stylesheet" href="/bower_components/bpg-arial/css/bpg-arial.css">
```

### IE Syntax (Optional)

Optional support for IE 8 or below.

```html
<!--[if lt IE 9]>
<link rel="stylesheet" href="/bower_components/bpg-arial/css/bpg-arial.ie.css">
<![endif]-->
```

### Bulletproof Syntax (Old Way)

Or if you prefer [Bulletproof @font-face syntax](http://www.paulirish.com/2009/bulletproof-font-face-implementation-syntax/), include the following css.

```html
<link rel="stylesheet" href="/bower_components/bpg-arial/css/bpg-arial.legacy.css">
```

### Minified

All those 3 css files have minified versions with suffix: `.min`. Example:

```html
<link rel="stylesheet" href="/bower_components/bpg-arial/css/bpg-arial.min.css">
```

### Final Step

Finally, after including font files to your project, place the following code to your stylesheets, or use another css selector instead of `body`.

```css
body {
    font-family: 'BPG Arial', sans-serif;
}
```

## Browser Support

**Modern Syntax**, which contains only: `.woff` and `.woff2` files is supported in the following browsers:

| Chrome | Safari | Firefox | Opera | IE   | Android |  iOS  |
| ------ | ------ | ------- | ----- | ---- | ------- | ----- |
| 5+     | 5.1+   | 3.6+    | 11.5+ | 9+   | 4.4+    | 5.1+  |

**IE Syntax** supports only IE6-8.

**Bulletproof Syntax** supports every major browser and it's versions, including IE6-8.

## Licence

The MIT License (MIT)

Copyright (c) 2015 Lado Lomidze.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.