Markade Server
===========

This is the development server for [Markade](https://github.com/Illyism/markade) with live build and reload capability

This repo is used mainly as sugar for [Markade](https://github.com/Illyism/markade). It runs a file watcher on the base directory and creates a static server in the output directory.

Installation
------------

You need node.js and npm. You should probably install this globally.

**Npm way**

	npm install -g markade-server


Version history
---------------

* v0.6.4
	- Forked from [Live-Server](https://github.com/tapio/live-server).
	- Added a callback to the LiveServer.change on .jade and .md files that returns the filePath.
* v0.6.3
	- See the the parent git from [Live-Server](https://github.com/tapio/live-server).


License
-------

Uses MIT licensed code from [Connect](https://github.com/senchalabs/connect/) and  [Roots](https://github.com/jenius/roots) and [Live-Server](https://github.com/tapio/live-server).

(MIT License)

Copyright (c) 2015 Ilias Ismanalijev

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
