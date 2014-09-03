# Media queries mixins for Stylus

# Installation

```bash
$ curl -O https://raw.githubusercontent.com/betaagency-os/stylus-mediaqueries/master/mediaqueries.styl
```

```styl
@include 'mediaqueries'
```

## Mixins:

```
+min-screen(width)                      // shortcut for @media screen and (min-width ...)
+max-screen(width)                      // shortcut for @media screen and (max-width ...)
+screen(min-width, max-width)           // shortcut for @media screen and (min-width ...) and (max-width ...)
---
+min-screen-height(height)              // shortcut for @media screen and (min-height ...)
+max-screen-height(height)              // shortcut for @media screen and (max-height ...)
+screen-height(min-height, max-height)  // shortcut for @media screen and (min-height ...) and (max-height ...)
---
+iphone3                                // only iPhone (2, 3G, 3GS) landscape & portrait
+iphone3(landscape)                     // only iPhone (2, 3G, 3GS) only landscape
+iphone3(portrait)                      // only iPhone (2, 3G, 3GS) only portrait
---
+iphone4                                // only iPhone (4, 4S) landscape & portrait
+iphone4(landscape)                     // only iPhone (4, 4S) only landscape
+iphone4(portrait)                      // only iPhone (4, 4S) only portrait
---
+iphone5                                // only iPhone (5) landscape & portrait
+iphone5(landscape)                     // only iPhone (5) only landscape
+iphone5(portrait)                      // only iPhone (5) only portrait
---
+ipad                                   // all iPads (1, 2, 3, 4, Mini) landscape & portrait
+ipad(landscape)                        // all iPads (1, 2, 3, 4, Mini) only landscape
+ipad(portrait)                         // all iPads (1, 2, 3, 4, Mini) only portrait
---
+ipad-retina                            // only iPad (3, 4) landscape & portrait
+ipad-retina(landscape)                 // only iPad (3, 4) only landscape
+ipad-retina(portrait)                  // only iPad (3, 4) only portrait
---
+hdpi(ratio)                            // devices with hidpi displays (default ratio: 1.3)
```


## Stylus version

- **Author**: Aleksej Kamynin
- **Repository**: https://github.com/betaagency-os/stylus-mediaqueries
- **WWW**: http://betaagency.ru


## Sass version

- **Author**: Rafal Bromirski
- **Repository**: https://github.com/paranoida/sass-mediaqueries
- **WWW**: http://paranoida.com/
- **twitter**: http://twitter.com/paranoida
- **dribbble**: http://dribbble.com/paranoida

## The MIT license

Copyright &copy; 2014 [Aleksej Kamynin](http://betaagency.ru)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
