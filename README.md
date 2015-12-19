# bintoc
Binary file to C source code converter

Saves all data from a binary file into a C file with two global variables: one stores data as an array of bytes, another stores file size (in bytes). Also creates header file with the same name

Known application flags:
* -f, --file <filename>: binary file to convert
* -V, --variable <name>: alternative variable name to store data
* -v, --verbose:         show more info
* -c, --color:           color output
* -h, --help:            show help

Note that variable name should have only latin letters [A-Z,a-z], digits [0-9] (not the first character) or underlines '_'. Default variable name is transformed file name
