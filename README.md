# JNetSend - README

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.10072.png)](http://dx.doi.org/10.5281/zenodo.10072)

**JNetSend** is an app created back in 2002 with the intent to provide a *pretty* interface for chat via `net send` (command line) in a WinNT based network.

The goal back then was replace a Visual Basic version of a similar app in the company where I did my internship.

**Note**: the code is poorly commented and a *little* messy :-)

## Requirements
 * JRE 1.4 or later
 * Ant 1.7 or later (`build.xml` was generated by Eclipse recently)
 * Works only in Windows workstations in WinNT network since it depends on `net send` service.

## Usage
```cmd
> cd <installation folder>
> java -jar JNetSend.jar
```

## MIT License
JNetSend - Copyright (c) 2002-2014 Pablo O Vieira 

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
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
