# Mehr Nastaliq Web Font

[![npm version](http://img.shields.io/npm/v/mehr.svg?style=flat)](https://npmjs.org/package/mehr "View this project on npm")
[![npm](https://img.shields.io/npm/dt/mehr.svg)]()
[![font version](https://img.shields.io/badge/font_version-2.0-blue.svg)]()
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg?colorB=9b59b6)](http://opensource.org/licenses/MIT)

A simple package providing the [Mehr Nastaliq Web](http://csalt.itu.edu.pk/urdufont/) font-face.
The font was created by Muhammad Zeeshan Nasar following the calligraphy of Nasrullah Mehr, and licensed with the Creative Commons Attribution-ShareAlike license.

<p align='center'>
<img src='https://cdn.rawgit.com/abbassiddiqi/mehr/ee8eb4df/sample.png' width='370' alt='mehr sample'>
</p>

## Features
- Faster rendering speed as compared to other Nastaliq fonts
- OTF Font file size reduced up to an amazing 108 kb only
- Best look according to National Calligraphic Standards
- Open Type, character based, Lahori Nastaliq Font
- Aaraab and marks support
- Limited Kashida support
- Reduced line height

## Installing

Assuming you have [NodeJS](http://nodejs.org/), [NPM](https://www.npmjs.com/) and [Bower](http://bower.io/) installed globally just open up a terminal, navigate to your projects root directory and then execute

```sh
# install via NPM
$ npm install mehr --save

# install via Bower
$ bower install mehr --save
```

## Usage
```html
<!-- Just add the following stylesheet link to your html file: -->
<link rel="stylesheet" href="https://unpkg.com/mehr/mehr-font.css">
```

```css
/* or import font stylesheet from within your css file */
@import url(//unpkg.com/mehr/mehr-font.css);
```

Then use provided font-face it in your CSS:

```css
h1 {
  font-family: Mehr;
}

p.quote {
  font-family: Mehr;
}
```

## License
This package is available under the [MIT license](https://github.com/abbassiddiqi/mehr/blob/master/LICENSE) and the Mehr Nastaliq Web font is available under the [Creative Commons Attribution-ShareAlike (BY-SA) License](https://creativecommons.org/licenses/by-sa/4.0/).
