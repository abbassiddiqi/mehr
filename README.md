# Mehr Nastaliq Web Font

[![npm version](http://img.shields.io/npm/v/mehr.svg?style=flat)](https://npmjs.org/package/mehr "View this project on npm")
[![npm](https://img.shields.io/npm/dt/mehr.svg)]()
[![font version](https://img.shields.io/badge/font_version-2.0-blue.svg)]()
[![font license](http://img.shields.io/badge/font_license-CC_BY--SA_4.0-brightgreen.svg?colorB=9b59b6)](https://creativecommons.org/licenses/by-sa/4.0/)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg?colorB=9b59b6)](http://opensource.org/licenses/MIT)

A simple package providing the [Mehr Nastaliq Web](https://mehrtype.com/product/mehr-nastaliq-web/) font-face.
The font was created by Muhammad Zeeshan Nasar following the calligraphy of Nasrullah Mehr.

<p align='center'>
<img src='https://cdn.rawgit.com/abbassiddiqi/mehr/ee8eb4df/sample.png' width='370' alt='mehr sample'>
</p>

## Features
- Faster rendering speed as compared to other Nastaliq fonts
- OTF Font file size reduced up to an amazing 108 kb only
- Best look according to National Calligraphic Standards
- Open Type, character-based, Lahori Nastaliq Font
- Aaraab and marks support
- Limited Kashida support
- Reduced line height

## Installing

Assuming you have [npm](https://www.npmjs.com/) installed, open up a terminal, navigate to your project root directory, and then execute:

```sh
$ npm install mehr --save
```

## Usage
```html
<!-- Add the following stylesheet link to your html file: -->
<link rel="stylesheet" href="https://unpkg.com/mehr/mehr-font.css">
```

```css
/* or import font stylesheet from within your CSS file */
@import url(//unpkg.com/mehr/mehr-font.css);
```

Then use the provided font-face in your CSS:

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
