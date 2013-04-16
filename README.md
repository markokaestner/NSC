NSC
===

*Number System Converter -- an [Alfred](http://www.alfredapp.com/) extension*

This workflow is based on the original one developed by [Hans-Helge B&uuml;rger](http://www.hanshelgebuerger.de "Hans-Helge Bürger - Webpage").

Whereas the original workflow was based on Python, this one uses the command line tool **bc**.

Features
--------
*NSC* can convert a number into another number system. Supported are:

* binary
* octal
* decimal
* hexadecimal
* any base between 2 and 16

Installation
------------
[Download](https://github.com/obstschale/NSC/raw/alfredextension/nsc-v2.0.alfredworkflow) the workflow and open with Alfred.

Usage
-----

### Keywords

* `decimal <decimal number>`
* `binary <binary number>`
* `octal <octal number>`
* `hex <hexadecimal number>`
* `convert <number> <base of number> <base of new system>`

### Examples

* `decimal 10` → result: B: 1010 // O: 12 // H: a
* `binary 1011` → result: D: 11 // O: 13 // H: b
* `octal 150` → result: D: 104 // B: 1101000 // H: 68
* `hex FF2` → result: D: 4082 // B: 111111110010 // O: 7762
* `convert 119 11 3` → result: D: 141 // Base 3: 12020 

Licensing
---------

Just like the original one, this workflow is licensed under [**CC BY 3.0**](http://creativecommons.org/licenses/by/3.0/ "Attribution 3.0 Unported (CC BY 3.0)") so you can use it for free.
