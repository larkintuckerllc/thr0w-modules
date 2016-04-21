README v0.0.1 / 21 APRIL 2016

# Thr0w Modules

## Introduction

The Thr0w Project is about building inexpensive and manageable interactive (or
not) digital displays using commodity hardware, web technologies, and open source
software. The key to this solution is having one computer behind each screen
networked to a single computer acting as a server. With this design, the
splitting and synchronization of content is accomplished through software.
More information on the Thr0w Project:

<https://github.com/larkintuckerllc/thr0w-server>

This repository provides a list of contributed Thr0w modules.

## Modules

**Thr0w Draw**

This repository provides a Thr0w module to provide a top drawing layer.

<https://github.com/larkintuckerllc/thr0w-draw>

**Thr0w Leaflet**

This repository provides a Thr0w module to create interactive maps using
the Leaflet library.

<https://github.com/larkintuckerllc/thr0w-leaflet>

**Thr0w SVG**

This repository provides a Thr0w module to create interactive scalable vector
graphics (SVGs).

<https://github.com/larkintuckerllc/thr0w-svg>

**Thr0w Windows**

This repository provides a Thr0w module to create stacked movable /
scrollable windows.

<https://github.com/larkintuckerllc/thr0w-windows>

## Contributing

Submit enhancement requests (e.g., ideas for or contributing modules) using the
Github Issues feature.

To contribute a module, it is recommended that one follows the development
guidelines / workflow of other contributed modules, e.g.,:

<https://github.com/larkintuckerllc/thr0w-draw>

It is required that:

The CSS and JavaScript need to be tested against the latest version of
Chrome Browser.

CSS entries are prefixed with *thr0w_MODULE_*; where *MODULE* is replaced
with a unique name for the module.

Modules are to be wrapped in an Immediately Invoked Function Expression
(IIFE); no globals.

Modules' expose their functionality as an appropriately named property on
the global *thr0w* object, e.g., *thr0w.draw* for the Thr0w Draw module.

## Credits

TODO

## Contact

General questions and comments can be directed to <mailto:john@larkintuckerllc.com>.

## License

This project is licensed under GNU General Public License.
