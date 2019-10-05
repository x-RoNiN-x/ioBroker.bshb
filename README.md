![Logo](admin/bshb-logo.jpg)
# ioBroker.bshb

[![NPM version](http://img.shields.io/npm/v/iobroker.bshb.svg)](https://www.npmjs.com/package/iobroker.bshb)
[![Downloads](https://img.shields.io/npm/dm/iobroker.bshb.svg)](https://www.npmjs.com/package/iobroker.bshb)
[![Dependency Status](https://david-dm.org/holomekc/iobroker.bshb.svg)](https://david-dm.org/holomekc/iobroker.bshb)
[![Known Vulnerabilities](https://snyk.io/test/github/holomekc/ioBroker.bshb/badge.svg)](https://snyk.io/test/github/holomekc/ioBroker.bshb)

[![NPM](https://nodei.co/npm/iobroker.bshb.png)](https://nodei.co/npm/iobroker.bshb/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/holomekc/ioBroker.bshb/master.svg)](https://travis-ci.org/holomekc/ioBroker.bshb) 

## bosch-smart-home-bridge adapter for ioBroker

This adapter allows to communicate with Bosch Smart Home devices. 
To achieve that it uses the [bosch-smart-home-bridge](https://github.com/holomekc/bosch-smart-home-bridge) library.

Still work in progress. Feedback appreciated.

## Changelog

### 0.0.5
* Just do the steps adapter-check is telling me
* Therefore, build files are part of git repo. So install via Github should be possible now

### 0.0.4
* Long polling added to reduce load
* Set of state values is possible now
* Code cleanup

### < 0.0.4
* certificate generation added
* first attempts to creat ioBroker objects, states, etc.

## License

MIT License

Copyright (c) 2019 Christopher Holomek <holomekc.github@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.