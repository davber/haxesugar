# haXe Sugar v0.3.0
> Updated 5/22/2009

## Description

A plugin (or "sugar") for the Espresso IDE, for haXe development. haXe is a multi-platform and multi-target language for both server- and client-based programming. See http://www.haxe.org for more information.

It currently contains the following pieces:

* Syntax Highlighting for all keywords, standard library classes and for most constructs
* Itemizers with custom icons (FamFamFam)
* Includes classes from the following targets: flash, flash9, neko and php

## Instructions

* To build the haXe sugar, just open the project (haXeSugar.xcodeproj) in XCode and hit Build.
* To deploy the sugar to Espresso, just double-click on the resultant haXe.sugar file.

> Note: future versions of this sugar will include build automation, which will in turn require the haXe compiler to
  be installed. Go to HaxeSite http://www.haxe.org for more information.

## Bugs / Issues!!

* The code for code completion is there, but for some mysterious reason they are never triggered
* The syntax is almost too involved, which might make it lose its context easily
* The navigation is currently messed up, showing only comment fragments, instead of classes and functions

## What's in the works

* Getting navigation back
* Code completion
* Support for hxDoc comments showing up when typing the name (or beginning of a name) of a method
* Better support for the haXe closure syntax

## Other Info

* This sugar was based on the AS3 sugar by Mike Murray, but is totally rewritten to more or less emulate a CFG for haXe, except for some literal and comment syntax which is borrowed from PHP's syntax files

## License

haXe Sugar is licensed under the MIT License Below:

The MIT License

Copyright (c) 2009 David Bergman

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

Using FamFamFam Silk Icons: http://www.famfamfam.com/lab/icons/silk/
