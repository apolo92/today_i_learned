####Para instalar el git hay que matar el proceso que no deja usar yum.

`ps -ef | grep yum`
`kill <yumProcesID>`

####Nos bajamos el git de la página oficial y lo pasamos por Filezilla.

####Ahora extraemos el tar.gz con

`tar xvfz ARCHIVO-GIT.tar.gz`

####Entramos en la carpeta extraida

`cd ARCHIVO-GIT`

####Lanzamos los siguientes comandos para instalar git 

`sudo ./configure`
`sudo make`
`sudo make prefix=/user install`
`git --version`

####Si no encuentra git tendrás que añadir la ruta de la instalación al archivo ~/.bash_profile

`sudo vim ~/.bash_profile`

    #... ~/.bash_profile ...
    PATH=$PATH:</path/to/git>
    export PATH
    #... ~/.bash_profile ...

`source ~/.bash_profile`

####Para ver las diferencias entre commits

`git diff`