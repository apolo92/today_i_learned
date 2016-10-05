`vim ~/.bashrc`

####Edit ~/.bashrc adding alias for commands you want to customize
####Note abous spaces: Respect the spaces when declaring alias, if you add spaces between <nameOfalias>='<commandToExecute>' it won't work!

    #... ~/.bashrc file ...
    alias <nameOfAlis>='<commandToExecute>'
    #... ~/.bashrc file ...

####Example

    #... ~/.bashrc file ...
    alias cdLongPath='cd /path/to/long/folder'
    #... ~/.bashrc file ...

####Now you need to restart the bash profile executing

`source ~/.bashrc`

####Then you can execute on the console 

`cdLongPath` 

####And it will execute

`cd /path/to/long/folder`

####You can list all the defined alias executing

`alias`