# nunito fontface

A simple package providing the [nunito](http://www.google.com/fonts/specimen/Nunito) fontface. This typeface has been created by Vernon Adams, check the [NunitoFont](https://github.com/vernnobile/NunitoFont) repository.
This has been forked diectly from  choffmeister's roboto-fontface package.

## Installing

Assuming you have [NodeJS](http://nodejs.org/), [NPM](https://www.npmjs.com/) and [Bower](http://bower.io/) installed globally just open up a terminal, navigate to your projects root directory and then execute

```
# install via NPM
$ npm install nunito-fontface --save

# install via Bower
$ bower install nunito-fontface --save
```


## Usage

There're several files in the `css/` subdirectory. Import them in your project
to have access to "nunito" font face:

* `css/nunito/nunito-fontface.css` - whole font family compiled to CSS
* `css/nunito/sass/nunito-fontface.scss` - whole font family in SCSS
* `css/nunito/less/nunito-fontface.less` - whole font family in LESS

* `css/nunito-condensed/nunito-condensed-fontface.css` - whole font family compiled to CSS
* `css/nunito-condensed/sass/nunito-condensed-fontface.scss` - whole font family in SCSS
* `css/nunito-condensed/less/nunito-condensed-fontface.less` - whole font family in LESS

* `css/nunito-slab/nunito-slab-fontface.css` - whole font family compiled to CSS
* `css/nunito-slab/sass/nunito-slab-fontface.scss` - whole font family in SCSS
* `css/nunito-slab/less/nunito-slab-fontface.less` - whole font family in LESS

Importing whole family may be unnecessary and lead to huge build, so if you are
using SCSS or LESS, you can import only individual weights by importing for example:

* `css/nunito/sass/nunito-fontface-black.scss`
* `css/nunito/sass/nunito-fontface-black-italic.scss`

## Hinting

Some of the included font files have [hinting](http://en.wikipedia.org/wiki/Font_hinting).

| Files    | Hinting |
|----------|---------|
| `.eot`   | ?       |
| `.svg`   | no      |
| `.ttf`   | ?       |
| `.woff`  | yes     |
| `.woff2` | ?       |

## License

```
Copyright 2014 The Nunito Project Authors (contact@sansoxygen.com)
This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL
```
