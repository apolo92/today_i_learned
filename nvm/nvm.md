####Install nvm
//TODO GLOBAL INSTALL
####You need to point your profile bash to nvm.sh file that you downloaded from the nvm repo

`sudo vim ~/.bash_profile`

    #... ~/.bash_profile ...
    export NVM_DIR="/path/to/nvm.sh/folder" #Not poiting nvm.sh directly just the folder that containts it, example: "/folder/folderWhithNvmShInside"
    [ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"
    #... ~/.bash_profile ...

`source ~/.bash_profile`

###Now you cau use nvm

`nvm -v`

####This will install last 6.x.x node version

`nvm install 6`

####To add alias to node versions, default is the de facto load for nvm

`nvm set default 0.12.1`

####To change betweeen node versions

`nvm use 4.5.0`

####.nvmrc

You can create a file named .nvmrc at root folder of your project and execute: `nvm use` then nvm will read the version to use here from this file

Please find a file example on this project
