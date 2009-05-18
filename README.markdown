# Flash Sugar v0.5.6 (formally ActionScript3 Sugar) 
> Updated 3/29/2009

## Description

An Espresso Sugar for ActionScript 3, Flex, and AIR development:

* Syntax Highlighting, Code Completion for many of the classes and reserved words
* Itemizers with custom icons (FamFamFam)
* Includes classes from the packages: flash, fl, adobe and air
* Compilation using Flex 3 SDK, Flash CS3/CS4
* Espresso is now somewhat aware of MXML files.

## Instructions

* Extract Flex 3 SDK to /Developer/SDKs/ as flex_sdk_3
* Support for CS3 and CS4 built in VIA flashcommand by Mike Chambers (Modified to work with CS4)

> Note: for now you can change the location for the flex sdk by opening:
> Flash.sugar/File Actions/Actions.xml and modifying < compiler-location >

> Note: for building support check out ActionBuild http://github.com/zado/actionbuild/tree/master

## NEW!

* Fixed placeholder theme
* Fixed itemizers, now any matching {} itemizes
* <mx:Script> syntax zone highlights AS3

## Usage
* If you select a *.as file in the project panel (not in workspace) and hit cmd + enter it will compile with MXMLC.
* If you have Flash CS4 installed and you have a *.fla file with the same name as the .*as file, it will instead be compiled with Flash SCS4
** (i.e.) Main.as + Main.fla = Flash CS4 compile with build command. Main.as alone = MXMLC compile.

## Bugs / Issues!!

* File actions are broken since 1.0.1. For build support check out ActionBuild http://github.com/zado/actionbuild/tree/master

## Whats in the works

* Better compilation support
> There needs to be a settings window for configuring the SDK, and other things related to the sugar

* Fixing a lot of the bugs with the syntax
* Smarter completion
> For example you only get completions based on on what you import. If you never import an air or fl package
> then you never see any of those completions in the list.

* MXML (getting even closer, got simple AS3 in the <mx:Script>)
> Going the be heavily based off of the XML+HTML Sugar with completion for AS3 within the MXML.

## Other Info

* Grabbed a lot of parts from the PHP sugar included with Espresso. Thanks.

## License

ActionScript3 Sugar is licensed under the MIT License Below

FlashCommand and this the <ActionScript 3 Sugar> is under MIT License:

The MIT License

Copyright (c) <year> <copyright holders>

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
