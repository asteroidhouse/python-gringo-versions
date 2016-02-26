# Compiled Versions of the Python `gringo` Module

This repository provides several versions of the `gringo` Python module developed by [Potassco](http:/potassco.sourceforge.net/) 
to control ASP solving from within Python programs. This module is written in C++, so you must use a version 
compiled for your specific environment. This repo currently contains versions of 
`gringo` compiled under Ubuntu 14.04 and MacOS 10.10.5, each with Python 2.7.x and Python 3.x.x. Details about the specific 
configurations used for each OS are below.

The documentation for the `gringo` module is [here](http://potassco.sourceforge.net/gringo.html).

## Version Information

**Current `gringo` version: 4.5.4**

The following table shows the exact versions of Python used for each OS configuration:

|              |      MacOS 10.10.5     | Ubuntu 14.04 (32-Bit) | Ubuntu 14.04 (64-bit) |
|:------------:|:----------------------:|:---------------------:|:---------------------:|
| **Python 2** | 2.7.11 (from Homebrew) |         2.7.6         |         2.7.6         |
| **Python 3** |  3.5.1 (from Homebrew) |         3.4.3         |         3.4.3         |


For each OS, we use the latest versions of Python that are available through the respective package managers.

For Ubuntu, this means the versions of Python you get when you run `sudo apt-get install python` and 
`sudo apt-get install python3` for Python 2 and Python 3, respectively.

For MacOS, this means the version of Python available through [Homebrew](http://brew.sh/); that is, what you get when you run `brew install python` and `brew install python3` for Python 2 and Python 3, respectively.

The directory structure of this repository is as follows:


```
├── python2
│   ├── linux-32
│   │   └── gringo.so
│   ├── linux-64
│   │   └── gringo.so
│   └── macos
│       └── gringo.so
└── python3
    ├── linux-32
    │   └── gringo.so
    ├── linux-64
    │   └── gringo.so
    └── macos
        └── gringo.so
```