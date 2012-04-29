## 1.4.0
_29th April 2012_

* Allow pdf/dxf output file to be specified in sketch options :output-file
* Override exit fn to not kill the current process.
* Use exit to ensure pdf/dxf file is written.

## 1.3.0
_19th April 2012_

Update for Clojure 1.4.0 compatibility

## 1.2.0
_11th April 2012_

Additions:

* Catch exceptions in draw fn by default and print exceptions to stdout. Each exception caught also causes the draw fn to sleep for 1s to throttle exception printing. This can be turned off by specifying `:safe-draw-fn false` in the sketch options.

## 1.1.0
_11th April 2012_

Additions:

* Added `:decor` sketch option to allow user to toggle frame decorations.

Fixes:

* Fixed outdated sketch docstring.

## 1.0.0
_7th April 2012_

First release!