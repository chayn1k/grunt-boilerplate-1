# [Grunt-Boilerplate]

## Table of contents

 - [What's included](#what-s-included)
 - [Installation](#installation)
 - [First Run](#first-run)
 - [Author](#author)
 - [Copyright and license](#copyright-and-license)

## What's included

Within the download you'll find the following directories and files, logically grouping common assets. You'll see something like this:

```
grunt-boilerplate/
├── assets/
│   ├── main/
│   ├── temp/
│   ├── vendor/
├── dist/
│   ├── assets/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   ├── js/
│   └── index.html
├── bower.json
├── gruntfile.js
├── package.json
└── README.md
```

## Installation

Run all the commands from console:

 - [Install Node.Js](http://nodejs.org/).
 - [Install Git](http://git-scm.com/download).
 - Add Git to Windows 7 Path.
 	Right-Click on My Computer
	Click Advanced System Settings link from the left side column
	Click Environment Variables in the bottom of the window
	Then under System Variables look for the path variable and click edit
	Add the pwd to git's bin and cmd at the end of the string like this:
	
	`;C:\Program Files (x86)\Git\bin;C:\Program Files (x86)\Git\cmd
 - Install Grunt globally
 	`npm install -g grunt-cli`
 - Install Bower globally
 	`npm install -g bower`
 - Fix of Bower issue on windows 7
 	`git config --global url."https://".insteadOf git://`


## First Run
 - Clone this git or download it and unzip it in a folder
 - From command line browse to your folder and run this command
 	`grunt install`
 - To start developing run this command
 	`grunt development`
 - Run this command for help
 	`grunt help`


## Author

**Luca Zampetti**

- <http://github.com/actarian>


## Copyright and license

Code and documentation copyright 2014 Websolute, Srl. Code released under [the MIT license](LICENSE). Docs released under [Creative Commons](docs/LICENSE).
