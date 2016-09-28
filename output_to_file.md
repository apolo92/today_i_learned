`ls /path/to/folder > /path/to/file/output.txt`

####">" will save the output of a command to a file (overriding it) for proper reading
####ls command is just an example you can use another one

`ls /path/to/folder >> /path/to/file/output.txt`

####">>" this will append the result if the file already exist

`ls | grep <filter> >> output.txt`
####You can also filter with grep