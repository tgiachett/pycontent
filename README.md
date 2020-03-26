# pycontent
Script that creates JSON manifest of files in a provided directory
#Installation
Invoke path to script or place in /bin or other $PATH directory. Only Posix paths currently supported. Only JSON supported.


## usage: content [-h] [-e EXTENSION] [-o OUTPUT] [-rel RELATIVE] [-abs] directory

positional arguments:
  directory             input directory, if not specified, current directory

optional arguments: \n
  -h, --help            show this help message and exit \s\s
  -e EXTENSION, --extension EXTENSION
                        Indicate file extension to be processed. If not specified default is all (*) \s\s
  -o OUTPUT, --output OUTPUT
                        Specify output filename (JSON only currently), default is ./manifest.json \s\s
  -rel RELATIVE, --relative RELATIVE
                        Use relative path, include what directory to start from \s\s
  -abs, --absolute      Use absolute path to prepend to files \s\s
