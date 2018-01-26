# arcticfox-config

[![Dependency Status](https://david-dm.org/hobbyquaker/arcticfox-config/status.svg)](https://david-dm.org/hobbyquaker/arcticfox-config)
[![devDependency Status](https://david-dm.org/hobbyquaker/arcticfox-config/dev-status.svg)](https://david-dm.org/hobbyquaker/arcticfox-config?type=dev)
[![Build Status](https://travis-ci.org/hobbyquaker/arcticfox-config.svg?branch=master)](https://travis-ci.org/hobbyquaker/arcticfox-config)
[![Github All Releases](https://img.shields.io/github/downloads/hobbyquaker/arcticfox-config/total.svg)]()
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

> Configuration Tool for Vape Battery Mods with Arcticfox Firmware. Works on MacOS and Linux.

![Screenshot](screenshot.png "Screenshot")


![Screenshot](screenshot2.png "Screenshot")


### Download

#### macOS

Go to the [latest release page](https://github.com/hobbyquaker/arcticfox-config/releases/latest) and download the 
arcticfox-config-x.x.x.dmg file.

#### Linux

On the [latest release page](https://github.com/hobbyquaker/arcticfox-config/releases/latest) you can find a .deb file, 
a .rpm file and a .tar.gz that should work on other distributions.

For USB access with an unprivileged user you need udev rules, see 
[Issue #25](https://github.com/hobbyquaker/arcticfox-config/issues/25)
The .deb and .rpm packages install these udev rules automatically and create a group `arcticfox`. You have to add you 
user to this group (`usermod -a -G arcticfox username`).


### Usage

Start the Application, connect your Arcticfox Device.


### Contributing

Clone the repo, do `npm install` in the project root. Use `npm start` to start the application in debug mode.
Depending on your installed Node.js version it might be necessary to rebuild the USB HID module:
`npm run rebuild`.

If you want to do a build on your own you can find hints on dependencies in 
[Issue #23](https://github.com/hobbyquaker/arcticfox-config/issues/23).


### Related

* https://github.com/hobbyquaker/arcticfox-monitor - A device monitoring tool for vape battery mods with Arcticfox firmware. Works on macOS and Linux.
* https://github.com/hobbyquaker/arcticfox - a Node module that abstracts the HID communication with the Arcticfox 
firmware and is also used by this project.
* https://github.com/hobbyquaker/dna-monitor - a macOS and Linux device config for battery mods with the DNA chipset.


### Credits

Based on the work of [NFE Team](https://nfeteam.org/)

* https://github.com/maelstrom2001/ArcticFox
* https://github.com/TBXin/NFirmwareEditor


This software uses [Highcharts](http://www.highcharts.com/) which is free __only for non-commercial use__.


### License

GPLv3

Copyright (c) Sebastian Raff
