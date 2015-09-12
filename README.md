# Liri Browser
A minimalistic material design web browser written for Papyros (https://github.com/papyros/)

See http://papyros.io for more information about Papyros.

[![GitHub license](https://img.shields.io/github/license/liri-browser/liri-browser.svg)](https://github.com/liri-browser/liri-browser/blob/master/LICENSE)
[![](https://img.shields.io/github/issues-raw/liri-browser/liri-browser.svg)](https://github.com/liri-browser/liri-browser/issues)
[![GitHub release](https://img.shields.io/badge/release-0.2-red.svg)](https://github.com/liri-browser/liri-browser/releases)
[![Join the chat at https://gitter.im/tim-sueberkrueb/material-browser](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/liri-browser/liri-browser?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## About
Our goal is it to create a minimalistic and simple, yet unique webbrowser that gets out of your way and lets you concentrate on the content. 
Liri's user interface is designed according to Google's Material Design which leads to a clean and beautiful interface.

The name "liri" comes from the Albanian word for freedom. Liri Browser was former named "Material Browser".

## Demo
<a href="http://www.youtube.com/watch?feature=player_embedded&v=7CbvpyzsQ0g" target="_blank"><img src="http://img.youtube.com/vi/7CbvpyzsQ0g/0.jpg" alt="video" width="240" height="180" border="10" /></a>

https://youtu.be/7CbvpyzsQ0g

## Screenshots
![Screenshot](screenshots/screenshot_01.png)
![Screenshot](screenshots/screenshot_02.png)

## Translations
Please help us translating this application! Read this guide to get started:
https://github.com/liri-browser/liri-browser/wiki/Translations

## Downloads
Check out the [downloads section](https://github.com/liri-browser/liri-browser/releases) and download the package for your platform.

### Linux
* Download `liri-browser-X.X-linux-portable.zip`
* Extract the files
* Run `run-liri.sh` inside the extracted directory

### Ubuntu Touch
* Download `liri-browser.timsueberkrueb_X.X_multi.click` on your device
* Open the terminal app or connect remotely by using adb shell or SSH
* `cd` into your Downloads directory
* Run `pkcon --allow-untrusted install-local liri-browser.timsueberkrueb_X.X_multi.click`

### Windows
TBD

### Mac OS X
TBD

## Build on Linux

### Simple Installation Script
If you just want to try Liri Browser out you can use our simple installation script. It will download and install Qt 5.5 and all necessary dependencies:

https://gist.github.com/tim-sueberkrueb/bdaae352cc6dcaca19b3

### Dependencies
* Qt 5.5 and QtWebEngine 1.1 (http://qt.io)
* qml-material (https://github.com/papyros/qml-material)

### Instructions
* Install Qt 5.5 (https://www.qt.io)
* Install qml-material
  * git clone https://github.com/papyros/qml-material.git
  * cd qml-material
  * qmake
  * make
  * make check # Optional, make sure everything is working correctly
  * sudo make install
 
### Build and Run
  * git clone https://github.com/liri-browser/liri-browser.git
  * cd liri-browser
  * qmake
  * make
  * run liri-browser executable

## Copyright and License
(C) Copyright 2015 by Tim Süberkrüb and contributors

See CONTRIBUTORS.md for a full list of contributors.

This application is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

See LICENSE for more information.
