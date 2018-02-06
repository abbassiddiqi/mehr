# Mehr Nastaliq Web Font

A simple package providing the [Mehr Nastaliq Web](http://csalt.itu.edu.pk/urdufont/) fontface. The font was created by [Muhammad Zeeshan Nasar](https://www.facebook.com/mzishannasar) following the calligraphy of Nasrullah Mehr.

Mehr Nastaliq Web OTF is the first font of Mehr font family, contains approximately 470 glyphs, including symbols and English support. This font allows Urdu computing on all platforms supporting OTF specifications e.g. Microsoft Windows, Unix, Linux, and Android. This font also enables web publishing, and electronic communication in Urdu using existing software (without any plug-ins) supporting OTF specifications, e.g. Google Chrome, Internet Explorer, Netscape Navigator, Mozilla and Safari.

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

Then use provided font-faces it in your CSS:

```css
h1 {
  font-family: Mehr;
}

p.quote {
  font-family: Mehr;
}
```
