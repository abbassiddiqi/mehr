# Mehr Nastaliq Web Font

[![npm version](http://img.shields.io/npm/v/mehr.svg?style=flat)](https://npmjs.org/package/mehr "View this project on npm")
[![npm](https://img.shields.io/npm/dt/mehr.svg)]()
[![font version](https://img.shields.io/badge/font_version-1.0_beta-blue.svg)]()
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg?colorB=9b59b6)](http://opensource.org/licenses/MIT)

A simple package providing the [Mehr Nastaliq Web](http://csalt.itu.edu.pk/urdufont/) fontface. The font was created by Muhammad Zeeshan Nasar following the calligraphy of Nasrullah Mehr.

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

```
# install via NPM
$ npm install mehr --save

# install via Bower
$ bower install mehr --save
```

## Usage
Just link provided CSS file to your page:

`<link rel="stylesheet" href="https://unpkg.com/mehr/mehr-font.css">`

or import it via your css file

`@import url(//unpkg.com/mehr/mehr-font.css);`

Then use provided font-faces it in your CSS:

```css
h1 {
  font-family: Mehr;
}

p.quote {
  font-family: Mehr;
}
```

## License
This package is available under [the MIT license](https://github.com/abbassiddiqi/mehr/blob/master/LICENSE) and the Mehr Nastaliq Web Font is available under the [Creative Commons License](https://creativecommons.org/licenses/by-sa/4.0/)
