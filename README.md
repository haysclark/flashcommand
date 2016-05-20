flashcommand
============
[![GitHub release](https://img.shields.io/github/release/haysclark/flashcommand.svg?maxAge=2592000)](https://github.com/haysclark/flashcommand/releases)

Command line tool written in python which can launch Flash authoring to compile FLAs into SWFs.

Requires
--------

 - Python

Installation
------------

Download the file and copy the _flashcommand_ file to somewhere within your PATH.
Make sure to make it executable by running the following command:

    chmod 755 flashcommand

Usage
-----

    flashcommand -e | -c | -p [-v] [-x] (-s <sourcefile>) ([-o] <exportpath>) ([-t] <timeout>)([-d]<tempdir>) [-j]

*Options and arguments:*

 -a : Prints version and about information.  
 -c : Specifies save and compact action.  
 -d : Specifies temp directory that will be used for temporary files. Optional.  
 -e : Specifies export action.  
 -h : Prints usage information.  
 -j : Specifies that the generated JSFL file should be printed. If this option is specified, Flash will not be executed.  
 -o : Specifies the output file if -e flag is also set. Optional. If not specified, file will be output to same directory as source.  
 -p : Specifies publish action.  
 -s : Specifies source file. Required.  
 -t : Specifies timeout value. Optional.  
 -v : Specifies verbose mode. Optional.  
 -f : Specifies that the Flash authoring version installed is a version other than Flash CS3  
 -x : Specifies whether Flash should be closed after it is done processing. Optional.  

Note: If you are using any version of Flash other than Flash CS3, then you need to specify the -f flag on the command line.
