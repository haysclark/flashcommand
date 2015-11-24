# Introduction #

How to use on OS X

# Requires #

[Python](http://www.python.org/)

# Usage #

usage: flashcommand -e | -c | -p [-v] [-x] (-s 

&lt;sourcefile&gt;

) ([-o] 

&lt;exportpath&gt;

) ([-t] 

&lt;timeout&gt;

)([-d] 

&lt;tempdir&gt;

) [-j]

Options and arguments:

```
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
```

Note : If you are using any version of Flash other than Flash CS3, then you need to specify the -f flag on the command line.

To install, download the file and copy the flashcommand file to somewhere within your path. Make sure to make it executable by running the following command:

chmod 755 flashcommand