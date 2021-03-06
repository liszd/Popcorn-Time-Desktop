# Popcorn Time

Allow any computer user to watch movies easily streaming from torrents, without any particular knowledge.

![Popcorn Time](http://ww1.sinaimg.cn/thumbnail/48910e01gw1eypg05v4dkj20e80e8js3.jpg)


***

## Getting Involved

Want to report a bug, request a feature, contribute or translate Popcorn Time? Check out our in-depth guide to [Contributing to Popcorn Time](CONTRIBUTING.md). We need all the help we can get! You can also join in with our [community](README.md#community) to keep up-to-date and meet other Popcorn Timers.

## Getting Started

If you're comfortable getting up and running from a `git clone`, this method is for you.

If you clone the GitLab repository, you will need to build a number of assets using grunt.

#### Quickstart:

1. `npm install -g grunt-cli bower`
1. `npm install`
1. `grunt build`
1. `grunt start`

If you encounter trouble with the above method, you can try:

1. `npm install -g bower grunt-cli` (Linux: you may need to run with `sudo`)
1. `cd desktop`
1. `npm install`
1. `bower install`
1. `grunt lang`
1. `grunt nodewebkit`
1. `grunt css`
1. `grunt start`

Optionally, you may simply run `./make_popcorn.sh` if you are on a linux or mac based operating system.

Full instructions & troubleshooting tips can be found in the [Contributing Guide](CONTRIBUTING.md)

<a name="community"></a>
## Community

Keep track of Popcorn Time development and community activity.


## Versioning

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, Popcorn Time will be maintained according to the [Semantic Versioning](http://semver.org/) guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>-<build>`

Constructed with the following guidelines:

* A new *major* release indicates a large change where backwards compatibility is broken.
* A new *minor* release indicates a normal change that maintains backwards compatibility.
* A new *patch* release indicates a bugfix or small change which does not affect compatibility.
* A new *build* release indicates this is a pre-release of the version.


***

If you distribute a copy or make a fork of the project, you have to credit this project as source.
	
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
 
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
 
You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/ .

***
 
Copyright (c) 2015 Popcorn Time Foundation - Released under the [GPL v3 license](LICENSE.txt).