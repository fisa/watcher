## About watcher
Checks continuously a web page for changes.
Released under the [GPLv3 license](https://gnu.org/licenses/gpl.html).

Watcher is a bash script used to check continuously static web pages in order to detect changes. This is useful, for example, if you are waiting for some kind of results that will be published in few hours, but you don't know exactly when.

Watcher has been developed for Mac OS X, it has been tested also on Ubuntu Linux. It requires curl (`sudo apt-get install curl`).


## Usage example
You need a terminal.
This displays the help of watcher:

	$ cd path/to/watcher/folder
	$ ./watcher -h

Example to check a web page:

	$ cd path/to/watcher/folder
	$ ./watcher -u "http://en.wikipedia.org/wiki/Bash_(Unix_shell)"


## Changelog:

### Version 1.0 - December 06 2013
* First public release
